# Q0: Why is this error being thrown?

    Because we don't have pokemon.

# Q1: How are the random Pokemon appearing? What is the common factor between all the possible Pokemon that appear? *

    The sample method in home_controller.rb is how the random pokemon are appearing. The common factor between all the possible Pokemon is that they are trainerless.

# Question 2a: What does the following line do "<%= button_to "Throw a Pokeball!", capture_path(id: @pokemon), :class => "button medium", :method => :patch %>"? Be specific about what "capture_path(id: @pokemon)" is doing. If you're having trouble, look at the Help section in the README.

    The following line prompts a "Throw a Pokeball!" button and when clicked sends the Pokemon id to the method located at the end of the patch. 

# Question 3: What would you name your own Pokemon?

    Little Anthony

# Question 4: What did you pass into the redirect_to? If it is a path, what did that path need? If it is not a path, why is it okay not to have a path here?

    I passed :back into redirect_to. It worked because it returns to you to the previous page.

# Question 5: Explain how putting this line "flash[:error] = @pokemon.errors.full_messages.to_sentence" shows error messages on your form.

    It grabs the error message from @pokemon.errors and shows it in a flash message at the top of the screen.

# Give us feedback on the project and decal below!

# Extra credit: Link your Heroku deployed app

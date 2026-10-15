Q1: Which column did you make nullable, and why that one and not another?

Answer: I made the is_blockbuster column nullable because some movie records might not have a value for it yet and I did not make the other columns nullable because fields like title, genre, rating, and year are needed to describe a movie.

Q2: Which step failed first for you, and what did the error say?
Answer: the first step for me is B after running php artisan tinker and App\Models\Movie::create(['title' => 'Spiderman']); and the error say Illuminate\Database\Eloquent\MassAssignmentException with message 'Add [title] to fillable property to allow mass assignment on [App\Model\Movie].

Q3: You changed no Blade file in Part D, yet your pages still work. Why not?

Answer: I did not change any Blade files because the controller still uses the same pages. I only changed where the movie data comes from, from the JSON file to the database. The pages still work because they use the same variables to show the movies.

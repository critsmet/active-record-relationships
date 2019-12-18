## Objectives:

- Review what an ORM is +
- Discuss ActiveRecord's purpose and Convention over Configuration +
- Setting up our database and models with ActiveRecord from scratch +
- Explore Rakefile possibilities +
- Define the purpose of a migration +
- Define a schema +
- Discuss altering databases and models with further migrations, rollbacks

- JUST committed the error. Like literally 2 seconds ago. No data has been added to the database since you made this mistake -> ROLLBACK
- You're deep in the database with a bunch of important data and need to make a change -> NEW MIGRATION
- EVERYTHING HAS GONE TO HELL AND YOU CAN'T FIGURE OUT THE ERROR -> DROP DB -- THE LAST RESORT


##Associations
- Review has-many-belongs-to-relationships and has-many-through (aka many to many)
- Create references to foreign keys in tables
- Set up the relationship in our model (Movie.rb file)
- Relating models in the console and elsewhere
- Seed file

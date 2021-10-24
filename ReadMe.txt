The Heroko mLab addOn for MongoDB is discontinued. Please see this link. https://docs.mlab.com/shutdown-of-heroku-add-on/


I found an alternative. I have followed the below URL to create and use a free MongoDB cloud database.
https://www.mongodb.com/developer/how-to/use-atlas-on-heroku/


MONGODB_URI = mongodb+srv://murali:murali@murali-east.slcnb.mongodb.net/murali-east?retryWrites=false&w=majority
Note - I had to use retryWrites=false for the Mongo atlas delete operation to work.
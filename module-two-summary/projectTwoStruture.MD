How to start your module two project:

Start with wireframes! Drawing what you want your app to look like helps when creating the models that make up the basic structure of your app. This helps when you think about what hbs files you'll need to create, your models, your data structure and the organisation of your app. The design does not need to be finished. Stick to your initial project idea- don't change mid week.

List all the features you need (sign up, login, log out etc). Mark the important ones, and do them first. If you have time you can add other features later. Spend time creating your models at the start and name things carefully- changing the names of your model later is hard and annoying because you use the names in so many different places (routes, forms etc) so something that was working could break if you change the number. 

When planning, divding up the tasks between you. Someone can take care of one route while someone else works on another. Or you can create one model each- it's up to you how you split the work. Make sure you talk to each other about what you're doing! Communication is very important. Make sure that you split the work equally and you both work on both the front end and the back end. 

Plan your models! You need one for your users and the second model is up to you.Things to account for- Will you have admins? Will they have to upload a picture when they sign up? Will there be default values? What is going to be required? 

Use Irongenerate to set up your app and install additional npm packages that you know you'll need.

Create different folders to help keep your code organised. Then create extra files - one for each model, plan your routes and split them into different files, think about how many hbs files you're going to need and how you can split them.

Add comments to your code. This is going to be important because you'll be sharing the code with your team. Every time you add, or change something, test the feature and then push to github. It's important to give your commits good messages because this will help you find what you are looking for later and shows your team what you have added/changed.

It's better to finish one feature before moving onto another- this includes adding basic styling. Doing css always takes longer than you expect so it's better to start adding it from the start. Decide if you're going to do all the css from scratch or if you're going to use a library like Bootstrap. It's good to know BEFORE you start doing css. 

If you want to make your app responsive, you need to plan for it. When doing your css, start with mobile first! Using Bootstrap makes responsive design much easier. 

Talk to each other! If they've added something you don't understand ask them to explain it to you. If you've installed an extra npm package, let them know so they know to do a `npm install` when they next do a pull request. Have checkpoints- set a time when you'll next have a 'meeting' or agree to meet after you've finished a feature. It's important to know what the other person is working on. 

Test every feature that you're working on as early as possible. If you're creating a route, check that it's working by rendering just a blank page, and then add the content. The more testing you do, the easier is it to debug. If you add five new things without testing and then something breaks you have no way of knowing exactly where the error is coming from. Testing is important 

Add DIFFERENT error messaages. Never use the same error message- make it specifc to the thing you're testing. This can be an emoji, a key word or anything else you can think of. this will be extremely useful when trying to find out where the error is coming from.

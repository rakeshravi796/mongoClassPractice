# Assignments

<h1>Building a Jira clone</h1>

<p>We can have a users table that will have information about the users , their roles and will have a user id.</p>
<p>THe second table would be Projects table with information about the project and also connected with users table as we will have the users involved in the project</p>
<p>Issues table will have information about the Issues and will be connected to the project table and will have data about which project it belongs to and the users involved in that issue will connect it with the users table.</p>
<p>We have a comments table that has comments created by the users and the issue and project they belong to.</p>

<h1>To Do app</h1>

<h3>Creating a database and adding 10 elements to the collection</h3>

![image](https://github.com/user-attachments/assets/21e34519-60e0-4057-a265-045c181460f0)

<h3>Showing all the elements in the collection</h3>

![image](https://github.com/user-attachments/assets/9a52e439-0a17-485c-88ae-c22ca519b880)

<h3>Adding a new column called completed</h3>

![image](https://github.com/user-attachments/assets/f6741480-55aa-4d36-89c3-81d4a8ec4650)

<h3>Updating completed status only using the Object Id</h3>

![image](https://github.com/user-attachments/assets/ff6b8cbb-1609-4594-b72c-566254345ffd)

<h3>Having a Updated At column</h3>

![image](https://github.com/user-attachments/assets/f3ab889b-6381-44a2-9711-9f59f855e90f)

<h3>Changing a document and also updating the updatedAt</h3>

![image](https://github.com/user-attachments/assets/133c1cde-a1b1-4fde-8218-affccc083146)

<h3>Getting the count</h3>

![image](https://github.com/user-attachments/assets/85958504-c740-4489-8572-c5638bbbcf1e)

<h3>Sorting</h3>

![image](https://github.com/user-attachments/assets/ffc741fb-8b86-4793-af6f-eb1eafdf299e)

<h3>Adding a due date</h3>

![image](https://github.com/user-attachments/assets/9137bd18-b239-499c-af95-debc038ae808)

<h3>History of commands</h3>

[
  'show dbs',
  'create todo',
  'create db todo',
  'use todo',
  'todo.basicTable.insertOne({"date": new Date() , "name" : "Finish Assignment" , "deadline" : "29-05-2025"})',
  'db.basicTable.insertOne({"date": new Date() , "name" : "Finish Assignment" , "deadline" : "29-05-2025"})',
  'db.basicTable.insertMany([{"date": new Date() , "name" : "Workout" , "deadline" : "29-05-2025","category" : "health"}] ;',
  'db.basicTable.insertMany([{"date": new Date() , "name" : "Workout" , "deadline" : "29-05-2025","category" : "health"}]) ',
  'db.basicTable.find({})',
  'db.books.find({deadline: "workout"})',
  'db.books.find({name: "workout"})',
  'db.books.find({name: "Workout"})',
  'db.basicTable.find(name: "Workout")',
  'db.basicTable.find({name: "Workout"})',
  'vadb.basicTable.insertMany([ { "date": new Date(), "name": "meditate", "deadline": "29-05-2025", "category": "health" }, { "date": new Date(), "name": "read a book", "deadline": "31-05-2025", "category": "education" }, { "date": new Date(), "name": "cook a new recipe", "deadline": "01-06-2025", "category": "hobby" }, { "date": new Date(), "name": "go for a run", "deadline": "02-06-2025", "category": "fitness" }, { "date": new Date(), "name": "attend a music concert", "deadline": "03-06-2025", "category": "entertainment" }, { "date": new Date(), "name": "visit a museum", "deadline": "04-06-2025", "category": "culture" }, { "date": new Date(), "name": "learn a new language", "deadline": "05-06-2025", "category": "education" }, { "date": new Date(), "name": "volunteer for a cause", "deadline": "06-06-2025", "category": "social work" }] );',
  'vadb.basicTable.insertMany([ { "date": new Date(), "name": "meditate", "deadline": "29-05-2025", "category": "health" }, { "date": new Date(), "name": "read a book", "deadline": "31-05-2025", "category": "education" }, { "date": new Date(), "name": "cook a new recipe", "deadline": "01-06-2025", "category": "hobby" }, { "date": new Date(), "name": "go for a run", "deadline": "02-06-2025", "category": "fitness" }, { "date": new Date(), "name": "attend a music concert", "deadline": "03-06-2025", "category": "entertainment" }, { "date": new Date(), "name": "visit a museum", "deadline": "04-06-2025", "category": "culture" }, { "date": new Date(), "name": "learn a new language", "deadline": "05-06-2025", "category": "education" }, { "date": new Date(), "name": "volunteer for a cause", "deadline": "06-06-2025", "category": "social work" }] );',
  'db.basicTable.insertMany([ { "date": new Date(), "name": "meditate", "deadline": "29-05-2025", "category": "health" }, { "date": new Date(), "name": "read a book", "deadline": "31-05-2025", "category": "education" }, { "date": new Date(), "name": "cook a new recipe", "deadline": "01-06-2025", "category": "hobby" }, { "date": new Date(), "name": "go for a run", "deadline": "02-06-2025", "category": "fitness" }, { "date": new Date(), "name": "attend a music concert", "deadline": "03-06-2025", "category": "entertainment" }, { "date": new Date(), "name": "visit a museum", "deadline": "04-06-2025", "category": "culture" }, { "date": new Date(), "name": "learn a new language", "deadline": "05-06-2025", "category": "education" }, { "date": new Date(), "name": "volunteer for a cause", "deadline": "06-06-2025", "category": "social work" }] )',
  'use todo',
  'db.basicTable.insertMany([ { "date": new Date(), "name": "meditate", "deadline": "29-05-2025", "category": "health" }, { "date": new Date(), "name": "read a book", "deadline": "31-05-2025", "category": "education" }, { "date": new Date(), "name": "cook a new recipe", "deadline": "01-06-2025", "category": "hobby" }, { "date": new Date(), "name": "go for a run", "deadline": "02-06-2025", "category": "fitness" }, { "date": new Date(), "name": "attend a music concert", "deadline": "03-06-2025", "category": "entertainment" }, { "date": new Date(), "name": "visit a museum", "deadline": "04-06-2025", "category": "culture" }, { "date": new Date(), "name": "learn a new language", "deadline": "05-06-2025", "category": "education" }, { "date": new Date(), "name": "volunteer for a cause", "deadline": "06-06-2025", "category": "social work" }] )',
  'db.basicTable.find({})',
  'use todo',
  'db.basicTable.find({})',
  'db.updateMany({},{$set : {"completed" : false)})',
  'db.updateMany({},{$set : {completed : false)})',
  'db.updateMany({},{$set : {completed : false}})',
  'db.basicTable.updateMany({},{$set : {completed : false}})',
  "db.updateOne({_id : ObjectId('6836e7573c6c05e33d6c4bd7')} , {$set : {completed : true}})",
  "db.basicTable.updateOne({_id : ObjectId('6836e7573c6c05e33d6c4bd7')} , {$set : {completed : true}})",
  'db.basicTable.updateMany({},{$set : {updatedAt : new Date()}})',
  "db.basicTable.updateOne({_id : ObjectId('6836e7573c6c05e33d6c4bd6')} , {$set : {completed : true , updatedAt : new Date()}})",
  'db.basicTable.count()',
  'db.basicTable.countDocuments()',
  'db.basicTable.find().sort()',
  'db.basicTable.updateMany({},{$set : {duedate : new Date()}})',
  "db.getCollection('basicTable').find({duedate:{$gte : new Date().getTime()-(20*60*1000)})",
  "db.getCollection('basicTable').find({duedate:{$gte : new Date().getTime()-(20*60*1000)}})"
]




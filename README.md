# To_Do_List
# HTML Code
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>To Do List</title>
    <link rel="stylesheet" href="main.css">
</head>
<body>

    <div class="container">
        <div class="todo-app">
            <h2>To-Do List <img src="images/icon.png"></h2>
            <div class="row">
                <input type="text" id="input-box" placeholder="Add Your Task">
                <button onclick="addTask()">Add</button>
            </div>
            <ul id="list-container">
            <!-- <li class="checked"> task 1</li>
            <li>task 2</li>
            <li> task 3</li> -->
            </ul>
        </div>
    </div>

<script src="main.js"></script>
</body>
</html>



# PROJECT DETAILS
This is a simple website completed by using  HTML, CSS, JAVASCRIPT
This website helps you to make a list of tasks to do in a day. 
In this you can add the tasks and remove them after completion of that task. The tasks will also save after refreshing the website.

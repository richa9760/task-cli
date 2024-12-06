Task-CLI is a command-line interface tool for managing tasks. This application allows users to create, update, delete, and manage tasks in a simple and efficient way. Tasks are stored in a JSON file, making data management straightforward.

Features
Add, Update, and Delete tasks
Mark tasks as "in progress" or "done"
List all tasks, tasks that are done, not done, or in progress
Persistent storage using a JSON file
Installation
Clone the repository to your local machine:


git clone https://github.com/richa9760/task-cli.git
Navigate to the project directory:


cd task-cli
Make the script executable (Linux/macOS only):


chmod +x task-cli
Usage
Adding a Task

./task-cli add "Your task description"
Listing All Tasks

./task-cli list
Listing Completed Tasks

./task-cli list --status done
Listing Pending Tasks

./task-cli list --status todo
Listing Tasks in Progress

./task-cli list --status in-progress
Updating a Task

./task-cli update <task_id> "Updated task description"
Marking a Task as In Progress

./task-cli update <task_id> --status in-progress
Marking a Task as Done

./task-cli update <task_id> --status done
Deleting a Task

./task-cli delete <task_id>
File Storage
Tasks are stored in a JSON file located in the project's directory. If the file does not exist, it will be created automatically.

Requirements
Python 3.x
Basic knowledge of command-line usage
Contributing
If you'd like to contribute to this project, feel free to fork the repository and submit a pull request. Your contributions are highly appreciated!

License
This project is licensed under the MIT License.

Acknowledgements
Thanks to the open-source community for providing the tools and frameworks that make this project possible.


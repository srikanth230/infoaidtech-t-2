class TodoList:
    def __init__(self):
        self.tasks = []

    def add_task(self, task):
        self.tasks.append(task)
        print("Task added.")

    def remove_task(self, task):
        if task in self.tasks:
            self.tasks.remove(task)
            print("Task removed.")
        else:
            print("Task not found.")

    def view_tasks(self):
        if self.tasks:
            print("Tasks:")
            for task in self.tasks:
                print(f"- {task}")
        else:
            print("No tasks.")

def main():
    todo_list = TodoList()

    while True:
        print("\n=== To-Do List App ===")
        print("1. Add task")
        print("2. Remove task")
        print("3. View tasks")
        print("4. Exit")

        choice = input("Enter your choice (1-4): ")

        if choice == "1":
            task = input("Enter the task: ")
            todo_list.add_task(task)
        elif choice == "2":
            task = input("Enter the task to remove: ")
            todo_list.remove_task(task)
        elif choice == "3":
            todo_list.view_tasks()
        elif choice == "4":
            print("Exiting...")
            break
        else:
            print("Invalid choice. Try again.")

if __name__ == "__main__":
    main()

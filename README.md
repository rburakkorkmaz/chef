# chef
Auto Cooker with Actor Framework implementation in LabVIEW


## <ins>GOALS</ins>
- checCreate basic recipe (Fire and Fire Duration) (DONE✅)
- Make sure Timer Actor sends a signal when duration is elapsed. (DONE✅)
- Create a recipe steping system with Timer Actor (DONE✅)
- Simultaneously update duration in step (DONE✅)
- Add new ways to keep track of duration. Use Time Delayed Send Message in
Timer Actor with counter logic (counter indivual small piece of elapsed time) (Worse than while loop approach
so I skip this step) (DONE✅)
- Refactor Chef Actor main event with self messages (DONE✅)
- Refactor all local variables to property nodes or private data (DONE✅)
- Implement State Machine to Chef actor event. Make sure you encapsulate state classes.
- Add more options to recipe
- Add recipe step execution animation such as fire in oven, roasting,etc.
- Add SubVI selection from Actor main UI in Launcher VI
- Send Telegram messages with each step done and whole meal completion status.

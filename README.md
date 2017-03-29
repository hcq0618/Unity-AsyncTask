# Unity-AsyncTask
async task in unity  similar to  Android AsyncTask

## 用法 Usage

AsyncTask task=AsyncTask.Create();
task.SetXXXX();
task.Excute();

## 方法 Method

**Create**:
创建一个异步任务实例
create an asynchronous task

**SetThreadMaxCount**:
设置线程池最大线程数
Set the maximum count of threads to thread pool

**SetDoInBackground**:
设置在子线程中执行的回调
Set the callback that executes on the child thread

**SetOnPostExecute**:
Set the callback that executes completed on the child thread

**Excute**:
执行任务
execute the task
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

设置异步执行完成后的回调

Set the callback that executes completed on the child thread

**Excute**:

执行任务

execute the task

## License

MIT License

Copyright (c) 2017 Hcq

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

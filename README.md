# First Real Software

We are going to try making our first real world software. I am going to have you create
a REST API using Python.

REST API is the backbone of the backend world and most of the services that you use (webpages, apps, etc) use REST APIs to receive data.

Python is by far one of the most popular languages for creating backend services. It's popular for many reasons, but at least for backend applications, it has one of the best package ecosystems which means if you need some feature, there is probably a python package for that.

I'll let you choose your stack, but here are some requirements:

- You need to make this using Python
- Use either Python Flask or FastAPI to create a REST API
- The REST API should take a name (string) and return it reversed.

If you have never used Python before, I'll give you quick basics:

1. Python is an intepreted language (so no need to compile your code like C or Java). However, you will need to invoke an interpreter to actually run your code, hence running python files like this: ```python some_file.py```.
2. It is popular to create "virtual environments". It is like creating a virtual clone of your main python installation so that when you install libraries, it doesn't mess up the original python installation. Follow online tutorials to get started [(like this)](https://www.freecodecamp.org/news/how-to-setup-virtual-environments-in-python/)
3. You will now need to know about ```.gitignore``` files. When you create your API, there will be lots of unrelated files such as the virtual environment files, sensitive documents that have access keys or if you use editors like VS Code, code editor settings files. We do not want to upload them into github for the public to see, so we use ```.gitignore``` file to tell git not to include those in our versioning. [Here's another good read](https://www.freecodecamp.org/news/gitignore-file-how-to-ignore-files-and-folders-in-git/).

The rest, you are going to have to google, but here is the end goal:

1. Your REST API should be runnable locally.
2. I should be able to send a POST request to the localhost REST API server
3. The API should return my input string in reverse.
4. A README.md page with some explainations on your API

Once this is done, I'll show you how to host these in AWS! Then we will get to making some front end web pages so we can all our REST APIs. Let me know if you need help at any point!

Good Luck!

\- Tyler
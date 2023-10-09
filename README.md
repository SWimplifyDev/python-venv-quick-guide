# Setting Up Your Python Playground: The Virtual Environment
![lab](/images/lab.jpg)


Welcome to our inaugural quick code guide! Today, we're diving into a fundamental skill for Python developers - setting up a virtual environment.

Picture this: Your own dedicated space, free from the clutter of conflicting packages, where you can experiment, create, and innovate with Python. That's exactly what a virtual environment offers. It's like having your very own laboratory, tailor-made for Python projects.

In this step-by-step guide, we'll walk you through the process of creating a virtual environment, enabling you to work on multiple projects with different dependencies, without any interference. Whether you're a beginner or a seasoned developer, mastering this skill is essential for efficient Python programming.

Ready to unlock the full potential of Python in your projects? Let's get started on this exciting journey!

## 1. Choose Your Python Playground
Open your terminal and navigate to the directory where you're going to create your Python project.
![image 1](/images/01.png)

## 2. Create a Home for Your Code
Let's start by making a cozy home for your code. Create a new folder using the command:
```console
mkdir my_first_API
```
![image 2](/images/02.png)

## 3. Step Inside Your New Space
Step into your freshly minted folder:
```console
cd my_first_API
```
![image 3](/images/03.png)

## 4. Time to Build Your Digital Fort
It's time to create a secret hideout, known as a virtual environment, for your Python adventures. Depeding on the python version you have installed on your machine, execute:
```console
python3.11 -m venv .venv
```
The dot at the beginning of .venv makes it magically hidden!
![image 4](/images/04.png)

## 5. Check if Your Hideout's Ready
Ensure that your secret base ".venv" has been created.
![image 7](/images/07.png)

## 6. Activate Your Virtual Adventure Zone
Activate your virtual environment to start your coding journey in isolation. Type:
```console
source /path_to_your_project/.venv/bin/activate
```
You'll know it's activated when your command line starts with (.venv).
![image 6](/images/06.png)

## 7. Summon Your First Coding Assistant
Let's bring in some help! Install your first package on your virtual environment:
```console
pip install pyjokes
```
![image 8](/images/08.png)
![image 9](/images/09.png)

## 8. Ready, Set, Code!
Create your first script, main.py, by tapping:
```
touch main.py
```
![image 10](/images/10.png)
![image 11](/images/11.png)
Open main.py with a text editor and let your creativity flow and fill it with code!
```python
import pyjokes

print(pyjokes.get_joke())

```
![image 12](/images/12.png)
Save changes.

## 9 Let the Laughter Begin
Fire up your terminal and run your script:
```console
python main.py
```

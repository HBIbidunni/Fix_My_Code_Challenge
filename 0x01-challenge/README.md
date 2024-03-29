# The ALX Project: 0x01. Fix my code
-------------

This is an optional __ALX__ project that focuses on __debugging and fixing code__. 
The goal is to take a given piece of code that contains bugs, identify the issues, 
and correct them to make the code function as intended. 
By completing this project, there is an enhancement of problem-solving skills, 
the ability to analyze code for errors, and gain experience in debugging techniques.

## Project Guidelines :heavy_check_mark: :white_check_mark:

These guidelines are to be followed when working on this project:

- Do not modify the test files in the tests/ directory.
- Maintain the original functionality of the code while fixing the issues.
- Analyze the code to identify any errors or bugs present. 
Common issues include syntax errors, incorrect variable assignments, 
improper function calls, or logical errors.
- Document any changes made by adding comments or updating the code's comments if necessary.
- Test the code thoroughly to ensure it behaves correctly after the fixes.


# Tasks :briefcase: :page_with_curl:
## 0. Server status

#advanced

I just started a new Flask project and the first thing I’m putting in place is a route for the status of my API (super important for a load balancer implementation).

But I don’t know why it’s not working…

Could you look at it and fix it please?

My code is [here](https://github.com/holbertonschool/0x01-``Fix_My_Code_Challenge``/tree/master/status_server/)
```
$ python -m api.v1.app 
 * Running on http://0.0.0.0:5000/ (Press CTRL+C to quit)
....
```

```
$ curl -XGET http://0.0.0.0:5000/api/v1/status
{
  "error": "Not found"
}
$
```

**Repo:**

* GitHub repository: ``Fix_My_Code_Challenge``
* Directory: ``0x01-challenge``
* File: [status_server/](./status_server/)
  
## 1. My square

#advanced

I love geometry!

Look [my square](https://github.com/holbertonschool/0x01-Fix_My_Code_Challenge/blob/master/square.py), it’s perfect? No? Should I change something?

**Repo:**

* GitHub repository: ``Fix_My_Code_Challenge``
* Directory: ``0x01-challenge``
* File: [square.py](./square.py/)
  
## 2. Step 2: User model

#advanced

I’m running into a serious problem!

I just start my OOP project and nothing works…

Could you help me please? My code is [here](https://github.com/holbertonschool/0x01-Fix_My_Code_Challenge/blob/master/user.py).

Thank you!

**Repo:**

* GitHub repository: ``Fix_My_Code_Challenge``
* Directory: ``0x01-challenge``
* File: [user.py](./user.py/)
  
## 3. Blog access

#advanced

I finished and deployed my Rails blog but people are contacting me because they can’t access any of my blog posts… Weird, it works for me…

Could you take a look and fix it? My code base is [here](https://github.com/holbertonschool/0x01-Fix_My_Code_Challenge/tree/master/blog).

Also, when you’re done, could you add a new feature please?

I would like to add a boolean ``online`` for each ``Post`` object with a default value ``true``. With this boolean, I will be able to hide/show some blog posts from the listing. I will also need a way to change this boolean in the ``Post#edit`` route. Could you do this for me?

Thank you!

**Repo:**

* GitHub repository: ``Fix_My_Code_Challenge``
* Directory: ``0x01-challenge``
* File: [blog](./blog/)
 
## 4. Never leave the office

#advanced

I’m coming back from 2 weeks of holidays in France and when I arrived at the office, the first words from my marketing co-worker were: “Hi, how was your holiday? by the way, I think I broke the website…”

**WHAT???**

Ok, let’s jump on it and [fix it](https://github.com/holbertonschool/0x01-Fix_My_Code_Challenge/tree/master/react-blog)!

Arf, I have also the pagination to fix… I didn’t have time before my break to look at it…

**Repo:**

* GitHub repository: ``Fix_My_Code_Challenge``
* Directory: ``0x01-challenge``
* File: [react-blog](./react-blog/)

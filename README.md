## ELM Framework: Effective Learning Method

Learning a new skill is challenging because if we learn something and don't use it, we will forget it. Another issue is that if you learn a new skill but don't experience real-life scenarios, you will not fully understand it. Therefore, we created the ELM framework to help you learn a new skill the right way.

### ELM Steps

1. [Goal](#1-goal)
2. [Acquire Basic Knowledge](#2-acquire-basic-knowledge)
3. [Summary](#3-summary)
4. [Use case learning method](#3-use-case-list)

    4.1 [Comprehensive use case list](#4-comprehensive-use-case-list)

    4.2 [Unlimited use case list](#unlimited-use-case-list)
5. [Project](#5-project)
6. [Improvements](#6-improvements)

### ELM Flowchart
![Effective Learning Method](https://github.com/mohanadwalo/effective-learning-methods/blob/main/elm.png)


#### 1. Goal
Describe the goal you intend to achieve.

```

Example 1 (Home aquarium) for anyone

I would like to set up a home aquarium and care for ornamental fish.
This includes selecting suitable filtration systems, feeding the fish, 
changing the water to maintain high quality, and setting up appropriate 
lighting systems.


Example 2 (Learning regex) for software developers

Using java regex, I would like to have the ability to search through any text, 
find specific patterns, and remove or update them.
Additionally, I want to be able to validate text against
a pattern to accept or reject it.
Finally, I want to extract useful data from large text.

```

#### 2. Acquire Basic Knowledge

We need to have the basics of the skill we are going to learn. We can do this by reading articles, a chapter or page from a book, or watching video tutorials.

Give yourself a few days to absorb  as much relevant information as possible.

Make sure not to waste time on useless resources.

#### 3. Summary

Based on the knowledge acquired in step 2, create any of the following:
  - Cheat Sheet (recommended)
  - Notes
  - Reference Documentation

### 4. Use case list
The use case approach suggests that we break down the larger skill into multiple use cases.

A use case is any place/situation where you can make use of the skill you intend to learn.

We should try to list as many use cases as possible so that in the future we can confidently use the learned skill when we experience the same use case.

We should organize the use cases into different categories so that they are easy to recall in the future.

Each category has multiple use cases and focuses on one area of the larger skill.

A use case is just a simple statement that describes what you intend to achieve.

We say that we have completed learning the new skill when we have completed all the use cases in all the listed categories.

We can distinguish between two different use cases types:

### 4.1 Comprehensive use case list
It is a skill where you can list almost all possible basic use cases, and you cannot miss or skip any basic use case.
  **For example,**
    Suppose you want to raise ornamental fish at home. We can organize the use cases into the following four categories:

**1. Prepare an Aquarium (Category)**

    - Choosing an aquarium size that fits your available space (use case)
    - Selecting the preferred shape: round, square, or other shapes (use case)

**2. Filtration (Category)**

    - Selecting a water filter (use case)
  
**3. Feeding (Category)**

    - Determining how many times to feed the fish per day (use case)
    - Choosing the type of food (use case)
    - Deciding the appropriate amount to feed each time (use case)
    
**3. Water Change (Category)**
```
  Determining how often to change the water in a week (use case)
  Learning how to change the water while the fish are inside the aquarium (use case)
  As you can see, we can't overlook any essential use cases. For example, can we raise ornamental fish without feeding them? Of course not. The same applies to other categories.
```
  This list is considered comprehensive because it covers all the use cases needed to maintain an aquarium at home.

### 4.2 Unlimited use case list
We can list as many use cases as possible, though we can't cover all of them. Let's look at an example involving programming languages, where regex can be used to search for patterns in text and then remove or replace them. However, regex has many more countless use cases.
Here We can list some categories and use cases:

**Query & Filter (Category)**
    
    - Extract protocol, domain name, and path from a URL (Use Case)
      Example: https://www.news.com/list?id=1
      Expected output:
      - Domain name: www.news.com
      - Path: /list?id=1

    - Extract query string parameters from a URL (Use Case)
      Example: https://www.news.com/list?id=1
      Expected output: 
      - id=1
  
    - Extract URL parts (Use Case)
      Example: https://www.news.com/list?id=1
      Expected output:
      - Protocol: https
      - Subdomain: news
      - TLD: com
      - Path: /list?id=1
      
    - Extract all URLs from text (Use Case)

**Working with Strings (Category)**

    - Remove unwanted characters/words from a text (Use Case)
    - Remove a collection of words from a text (Use Case)
    - Remove spaces at the beginning and end of a string and reduce multiple spaces between words to a single space (Use Case)
    - Remove a sentence from text (Use Case)
    - Scan text and add a newline after any period if there isn't one already, and capitalize the first word of the next sentence (Use Case)

**Formatting (Category)**

    - Format a decimal number (Use Case)
      Example: 522025 -> 522,025
    - Format a date (Use Case)
      Example: 20240510 -> 2024-05-10
    
As you can see, there are numerous use cases, making this an example of "unlimited use cases".

#### 5. Project(Optional)

Now that we have the foundational knowledge, including a reference document or cheat sheet, we’ve also built a strong understanding by listing all possible use cases.


**Note**
You can skip this step if you have already completed enough practical use cases, such as the regex example mentioned earlier. However, it is still recommended to complete this step. If the use cases provided were not practical enough, it is essential to work through this step before proceeding.

The next step is to build a project.

    - Come up with a project idea.
    - List all the skills you will need to complete the project.
    - Repeat the ELM for each skill.
    - Implement and build the project.

**Example:**

Let's say I am a software engineer with the following idea:

I want to build a news engine that allows uploading news written in a specific format from a file. The engine will parse the files and broadcast messages, with each message containing one news item with full details such as category, title, images, and body. Clients can subscribe to a specific category to receive notifications whenever a new message is published in that category.

To follow the ELM framework:

**(Project idea):**

```
I want to build a news engine that allows uploading news written in a specific format from a file. The engine will parse the files and broadcast messages, with each message containing one news item with full details such as category, title, images, and body. Clients can subscribe to a specific category to receive notifications whenever a new message is published in that category.

```

**(Required Skills list):**

Identify the required skills:

    - File Parser:
      Handling file types such as XML, CSV, and JSON.
    - Message Producer:
      Implementing a message queue system.
    - Subscription Manager:
      Managing client subscriptions.
    - Web Application Development:
      Creating a web application for clients to create accounts and subscribe to categories.

**Apply the ELM for each skill.**

**Implement and build the project.**



**6. Improvements & Suggestions**

    - Suggestions for improving the approach or process.
    - Best practices
    - Highlighting flaws: Acknowledging any limitations or shortcomings in the chosen methods and suggesting improvements.


#### See also

Cheat sheets [here](https://github.com/mohanadwalo/cheat-sheets)  
Learning a new language effectively [here](https://github.com/mohanadwalo/learning-a-new-language)  
Learn Java Through Practical Use Cases [here](https://github.com/mohanadwalo/java-use-cases)  


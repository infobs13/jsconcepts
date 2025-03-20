---
layout: default
title: Data datatypes datastructures
---

## Data  
**Data** refers to information that can be stored, transmitted, and processed by computers. It comes in various forms, such as numbers, strings, arrays, or complex structures like objects.  

- **Transmittable?** Yes! When you run `git push origin main`, you're transmitting data (1s and 0s) to a remote server. Every time you send an email, browse a website, or upload a file, you're transmitting data over the internet.  
- **Storable?** Absolutely! Open a file, write something, and save it—that’s storing data. From databases to simple text files, data storage is a fundamental aspect of computing.  

## Data Types  
In programming, **Data Types** define how data is categorized, used, and manipulated in a program. They help ensure that data is handled correctly and efficiently, preventing errors and optimizing performance.

Imagine a table in your study room with numbers, characters, strings, and floats randomly spread across it. This represents the universe of data. Now, neatly divide the table into four quadrants, like a coordinate plane:

- **1st Quadrant:** Whole numbers and decimals.  
- **2nd Quadrant:** Floating-point numbers.  
- **3rd Quadrant:** Individual characters.  
- **4th Quadrant:** Strings (sequences of characters).  

Why do we group them? Because they are inherently different. If all data were the same, we wouldn’t need categorization. Numbers can be added together to represent quantity, while adding two strings results in concatenation rather than numerical addition. Different data types require different operations—computers handle numbers mathematically, while strings are treated as sequences of characters. This fundamental difference is why they must be categorized and processed accordingly.

## Data Structures  
A **structure** is the way parts are arranged or organized to form a whole. It’s not just about strict order but about how components relate to each other.

The word **"structure"** naturally brings to mind concepts like **order, organization, and arrangement**. When discussing **data structures**, the word **"organize"** appears frequently because structuring data is fundamentally about arranging it efficiently.  

However, **"order"** in its strict sense often implies a sequence, such as **ascending or descending** order. But in **data structures**, organization isn’t limited to just sorting—it’s about structuring data in a way that optimizes key operations like **insertion, deletion, access, and lookup**.  

In essence, a **data structure** is a way of **organizing** data so that operations on it can be performed efficiently. The choice of structure—whether an **array, linked list, tree, or graph**—depends on the problem at hand and the specific operations we need to optimize.  

- In **language**, sentence structure defines how words are arranged (e.g., Subject-Verb-Object in English).  
- In **architecture**, building structure refers to how materials are organized to ensure stability.  
- In **data structures**, it describes how data is **organized in memory**, influencing how we store, access, and manipulate it efficiently.  

### Linear vs. Non-Linear Data Structures  
**Linearity is not about the values stored but about how they are arranged in memory.**  

- **Linear Data Structures**: Elements are arranged sequentially in memory. Each element has a direct predecessor and successor (except the first and last). Examples: Arrays, Linked Lists, Stacks, and Queues.  
- **Non-Linear Data Structures**: Elements are not arranged sequentially but rather in hierarchical or interconnected ways. Examples: Trees, Graphs, and Heaps.  

Understanding data structures is essential because how data is organized impacts efficiency, performance, and usability in a program.

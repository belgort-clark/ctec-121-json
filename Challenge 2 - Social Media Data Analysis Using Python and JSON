# **CTEC 121 Assignment: Social Media Data Analysis Using Python and JSON**

## **Assignment Overview**  
In this assignment, you will create a **command-line Python application** that retrieves and analyzes social media data from an external JSON file. Your program will:  
1. **Fetch and parse** a dataset containing user profiles, posts, comments, and likes.  
2. **Allow users to search for a specific user by username or user ID** to retrieve their profile details.  
3. **Display a user’s recent posts along with the number of likes and comments**.  
4. **Identify and display the user’s most popular post** based on the highest number of likes.  
5. **Handle errors gracefully**, ensuring the program does not crash if an invalid username or user ID is entered.  

This program must be run **exclusively from the command line**.  

## **Retrieve Social Media Data**  
Your script must fetch social media data from the following endpoint:  

**`https://raw.githubusercontent.com/belgort-clark/ctec-121-json/refs/heads/main/social_media.json`**  

This dataset contains:  
- **Users**: User ID, username, name, bio, and follower count.  
- **Posts**: Post ID, user ID, timestamp, content, number of likes, and number of comments.  
- **Comments**: Comment ID, post ID, user ID, and content.  

## **Features Your Script Should Support**  

### **1. Display User Information**
- The user runs the script with a **username or user ID** as an argument.
- The program fetches the corresponding **profile details**, including:
  - Full name  
  - Bio  
  - Follower count  
  - Total number of posts  
  - Total number of likes received on all posts  

### **2. Display Recent Posts**  
- The program should list the **last 3 posts** by the user, including:  
  - Post content  
  - Number of likes  
  - Number of comments  

### **3. Identify the Most Popular Post**  
- The program should analyze all posts by the user and determine which post has the **most likes**.  
- Display the post’s content and number of likes.  

### **4. Handle Invalid User Input**  
- If the user enters a username or user ID that does **not exist**, display an error message.  
- If no username or user ID is provided, display a list of available users and prompt the user to enter a valid one.  

## **Command-Line Execution**  
- The program should be executed with a username or user ID as an argument.  
- If no argument is provided, the program should list all available usernames and prompt the user to enter one.  

## **Valid Usernames for Testing**  
Your program should work with any of the following usernames from the dataset:  

```
tech_guru, nature_lover, fitness_fanatic, foodie_journey, travel_nomad,  
coding_master, bookworm23, music_addict, movie_buff, pet_lover,  
sports_fan, history_buff, art_enthusiast, gamer_pro, photography_freak,  
diy_crafter, sci_fi_fan, car_enthusiast, fashion_diva, news_junkie
```

If a user enters a username **not in this list**, the program should display an error message.

## **Hints & Tips**  
- Use the `requests` library to fetch the JSON data.  
- Use `sys.argv` to handle command-line arguments.  
- Store **users, posts, and comments** in dictionaries for efficient lookup.  
- If no username is provided, **print the available usernames**.  
- If an invalid username is entered, **print an error message**.  
- Use Python’s built-in `sorted()` function to find the most popular post.  

## **Submission Requirements**  
- Submit your Python script (`social_media.py`).  
- Your code should be **well-commented** to explain each step.  
- Ensure that your script runs **without errors** before submitting.  

## **Bonus Challenge**  
Modify your program to allow multiple usernames as arguments so that the program can display **comparisons between users** (e.g., who has the most followers or most-liked post).  

---

Happy coding! 🚀

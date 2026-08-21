# How to fix and customize your Birthday Website

To update this website with your own details, you need to open the `index.html` file in any code editor (like Notepad or VS Code) and make changes to the exact lines listed below.

---

## 1. Change the "NAME"
Look for the word **NAME** or **Name** on these exact lines and change it to the birthday person's actual name:

*   **Line 9:** `<title>Name's Birthday</title>` *(Changes the name on the browser tab)*
*   **Line 57:** `Click Here NAME,,` *(Changes the text on the envelope button)*
*   **Line 71:** `<span>Dear NAME ❤</span>` *(Changes the text in the first greeting card)*
*   **Line 132:** `<h4 class="username">To: NAME 💖...</h4>` *(Changes the text in the second open card)*

---

## 2. Change the Birthday Wish
You can update the long personalized birthday message on this exact line:

*   **Line 142:** Here you will see the text `check fix-web.me to wish, update name and change the photo`. Delete just this text and type your own personalized birthday paragraph in its place.

---

## 3. Change the Photos
To add your own pictures, it is highly recommended to place your new image files inside the `images/` folder. Then, go to the exact lines below in `index.html` and change the `src="..."` link to point to your new file name

*   delete the current unnamed.png from images and add your image to that exact same folder but keep the same name :unnamed.png  

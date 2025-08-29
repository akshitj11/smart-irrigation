This is a smart irrigation site i made at a hackathon named 'hackforge' at my univ. 
This is a major tool what is needed by every country , i think farming is the backbone of a country's economy and it is the one of the most important sectors for a country. 
So, why should we not make a futurised product for our farmers which consists of IOT controls as well as many unique features ,
that will reduce many extra expenses that a farmer has to deal with also a significant amount of labour costs.
features it contains are:
   automatic water valve controls (which farmer can control when to open the water valves for irrigation and for how much time.)
   it has a water requirement alert also , which will tell when the water is needed
   motion alert 
   fire alert
   weather alert(for unexpected weather situations)
   and our one of the most important feature *offline mode*:
                                    this is just an idea now but i will soon develop a way to implement it , whenever an area's internet is disrupted it automatically starts,
                                    all the features starts working without internet connectivity using radio signals.

all these features are backed the IOT , soil moisture sensors , motion sensors, radio signals , and more sort of signals.

<img width="465" height="281" alt="image" src="https://github.com/user-attachments/assets/32b65b29-384e-45c6-8974-b8b8a512b31d" />


*tech stacks i have used in these are as follows:*
Structure: HTML
What it is: The standard markup language for creating web pages.

Where it's used: The entire file is an HTML document. It defines all the structural elements you see on the page, such as the main container (<div id="app">), the header (<header>), the different panels or "cards" (<div>), buttons (<button>), and text (<h1>, <p>).

## Styling: Tailwind CSS
What it is: A utility-first CSS framework that allows for rapid styling directly within the HTML. Instead of writing separate CSS files, you use pre-built class names.

Where it's used: You can see Tailwind everywhere in the class="..." attributes of the HTML tags.

class="bg-white p-6 rounded-2xl": This creates a white card with padding and rounded corners.

class="grid grid-cols-2 gap-4": This creates the two-column layout for the control panels.

class="text-3xl font-bold": This makes the main title large and bold.

## Interactivity: Vanilla JavaScript
What it is: "Vanilla" just means it's standard, plain JavaScript without any additional frameworks like React or Angular.

Where it's used: All the logic and dynamic behavior of the app are handled in the large <script> block at the bottom of the file. This includes:

Language Switching: The changeLanguage function reads the selected language and updates all the text on the page from the translations object.

Timer Logic: The timerStartBtn.addEventListener function handles the countdown, updates the display every second, and automatically turns off the valve when the time is up.

Dashboard Updates: The updateDashboard function takes the calculated recommendation and dynamically changes the text, icon, and color of the main alert card.

## External Services: Google Fonts
What it is: A free library of fonts that can be easily included in web pages.

Where it's used: In the <head> section, you'll see <link> tags that connect to fonts.googleapis.com. This is crucial for making the non-English languages look good. The code loads specific fonts that support each script:

Noto Sans Devanagari: For Hindi and Marathi.

Noto Sans Gurmukhi: For Punjabi.

Noto Nastaliq Urdu: For Urdu.






<img width="1776" height="1020" alt="Screenshot 2025-08-30 031529" src="https://github.com/user-attachments/assets/35addc7e-badc-4a05-a8d6-50793dd179c2" />

<img width="1593" height="989" alt="Screenshot 2025-08-30 031547" src="https://github.com/user-attachments/assets/4889027d-39e5-4b95-924f-ef890813f961" />

<img width="1309" height="966" alt="Screenshot 2025-08-30 031556" src="https://github.com/user-attachments/assets/3f2efb74-8304-4451-bdfb-d8a3810164f7" />


<img width="1043" height="860" alt="Screenshot 2025-08-30 031608" src="https://github.com/user-attachments/assets/937632e3-a6d8-4727-b96a-fd84a8189c11" />






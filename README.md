# Cookie consent
## What is it? 
It's a website that tries to sell you a scammy course, and after a few seconds it shows you a popup window that asks for your data, again, in a scammy way. The website it's only to practice Javascript and a little of CSS, the information actually will not go to any other place.
This project is part of Module 5, where they teach you essential Javascript concepts. 
## What did I use?
I used HTML, CSS, and Javascript.
## Concepts learned for this project and practiced during it
  - **setTimeout()** to run a function after x milliseconds
    - ```Javascript
      setTimeout(function(){}, 3000) // will run after 3 seconds
      ```
  - **Forms** to make a form area in HTML, and improve input management in Javascript and accessibility.
    - `<label>` to add a description for the input
      - **for** property, to link the label with the input with the id passed as value, so for example, when the user clicks on the label, the focus goes to the input.
    - **type** property for `<input>` and `<button>`
      - for `<input>` is to declare which values the input accepts.
        - ```HTML
          <input type="number"/> <!--- Only accepts numbers --->
          ```
      - for `<button>` is to declare the function of the button. The default type in a form is "submit"
        - ```HTML
          <button type="button"><button> <!--- To make buttons that not activate the submit event --->
          ```
    - **name** input attribute, to later manage the data entered in Javascript, using FormData. 
    - **FormData** to manage the data entered in the form, in Javascript. 
      - ```Javascript
        const newFormData = new FormData(formHtmlElement)
        ```
      - `get()` to get the values entered in the form, using the name attribute to select the specific inputs.
        - ```Javascript
            const name = newFormData.get("name")
          ```
      
## Preview 
<img style="text-align:center" src="https://github.com/AlexMakowiecki/coworking-space-site/assets/122258496/343ba621-115c-4d5f-a863-6d2e8b9a511c" width="500px"/> 

## About Scrimba!


At Scrimba our goal is to create the best possible coding school at the cost of a gym membership! 💜
If we succeed with this, it will give anyone who wants to become a software developer a realistic shot at succeeding, regardless of where they live and the size of their wallets 🎉
The Frontend Developer Career Path aims to teach you everything you need to become a Junior Developer, or you could take a deep-dive with one of our advanced courses 🚀

- [Our courses](https://scrimba.com/allcourses)
- [The Frontend Career Path](https://scrimba.com/learn/frontend)
- [Become a Scrimba Pro member](https://scrimba.com/pricing)

Happy Coding!

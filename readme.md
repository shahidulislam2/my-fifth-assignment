Question and Answer--->>

1.What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?
ans: getElementById is a unic selector.It will select a unic variable. className could be multiple,we can get multiple element with same name.querySelector can select id,class,tag but only the first one.QuerySelectorAll can select multiple elements and multiple selectors also.

2.How do you create and insert a new element into the DOM?

ans: First choose where to create or find the parent and create an element (ex: document.createElement("div")), then put innerText into it and finally append the child into the parent you want

3.What is Event Bubbling and how does it work?

ans: From target phase to root phase or parent phase like it's bubbling. first capturing phase second target phase and last is bubbling phase final parent the way it's going back after getting targeted element it's called event bubbling

4.What is Event Delegation in JavaScript? Why is it useful?

ans: event deligation is a shortcut and eficient method for addEventListener. If I have 100buttons insted of using 100event listener we can use only one event listener in parent and we can acces every button element with bubbling.

5.What is the difference between preventDefault() and stopPropagation() methods?

ans: these two things solve different problems, when we use form element, it's assume a normal button to submit button.thats why it's not not working properly then we use preventDefault() so that the default value should remove. stopPropagation is to stop bubbling event normally capturing an item or element from parent to child and bubbling child to parent. we can stop bubbling with stopPropagation.


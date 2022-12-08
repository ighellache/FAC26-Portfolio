# 1. Check that passing a given input into our tests returns the expected output
test("Should add taskinput to list", () => { 

  const taskInput = document.getElementById("mytask");


  taskInput.value = "drink";

  const submitButton = document.querySelector("button[id='push']");
  submitButton.click();

  let result = document.querySelector("#tasks");
  
  equal(result.textContent.slice(73, 78), taskInput.value);
 
});

# 2. Write tests to mimic the behaviour of a user performing different actions
test('when add button is clicked, display task in the div id=tasks',()=>{
  const button = document.getElementById('push');
  button.click();
  const mytask = document.getElementById('tasks');
  if (document.body.contains(mytask)) {
    console.info(`Pass: Clicking add button displays task in the to do list`);
  } else {
    console.error(`Fail: Clicking add button does not display task in the to do list`);
  }
});

# 3. Write testable, modular functions
test('when add button is clicked, display task in the div id=tasks',()=>{
  const button = document.getElementById('push');
  button.click();
  const mytask = document.getElementById('tasks');
  if (document.body.contains(mytask)) {
    console.info(`Pass: Clicking add button displays task in the to do list`);
  } else {
    console.error(`Fail: Clicking add button does not display task in the to do list`);
  }
});
# 4. Write functions that add, remove or modify DOM nodes
test('when add button is clicked, display task in the div id=tasks',()=>{
  const button = document.getElementById('push');
  button.click();
  const mytask = document.getElementById('tasks');
  if (document.body.contains(mytask)) {
    console.info(`Pass: Clicking add button displays task in the to do list`);
  } else {
    console.error(`Fail: Clicking add button does not display task in the to do list`);
  }
});
# 5. Apply event listeners to HTML form elements
  <button id="newBtn" onclick="showtask()">What did I need to do again?</button>
# 6. Use scope to control what variables are accessible inside functions and blocks
const addBtn = document.getElementById("push");
# 7. Use CSS grid to create complex layouts

# 8. Use CSS grid to make layouts that adapt to the viewport size




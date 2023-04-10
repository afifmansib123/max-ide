#notes on variable

we created the page for a variable : variablepage. on there was a dialoge box. the box's visibility was binded to a variable called visvar01. it's value was set to false. so once the page was opened it was unseen. only visible if value set to true like any variable workd. then we put a button to change that false to true to make it visible. So finally when the button is pressed, the dialoge box is visible.

function makedialogevisible() {
    max.data.set('visvar01', true)
}  

this function was binded to a button that changed the state of the variable responsible for visibility.

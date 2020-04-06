https://github.com/Zackazt/bills-tutorial/blob/master/src/Components/App/App.css
[ ]css >>>>>

    //center  element in the screen horizontally

    margin: auto;
    border-radius: 15px 50px; 
    first value applies to top-left and bottom-right corners, and the second value applies to top-right and bottom-left corners:

[ ] in index.css >>>
    []body{
    
    background-image: url('./bg.jpg');
    box-sizing: border-box;
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center center;
}

[ ]add bootstrap >>>>


##################################### next  #####################################
[ ]AddBill component +css >>>
    rfc(snippet)

    remember! useState returns an array with 2 functions inside of it!
    1-st - initial value
    2-nd - function that updates that initioal value

** every time we change the input we are going to update the state with the value of that input
and its goin to be synchronisd with the value 

** useEffect == componentDidMount in class based comp method

[ ] Validation of inputs
[ ] Clear the form after submmition

##################################### next  #####################################
[ ]Context   
https://reactjs.org/docs/context.html
Context provides a way to pass data through the component tree without having to pass props down manually at every level.
    []create the context
    []provide a context value
    []consume the context value

    [ ]make changes in App.js file  !!!
##################################### next  #####################################
[ ] useEffect ('componentDidMount' in js version )
[ ]updateBills
    []spread operator 
    JavaScript | Spread Operator. Spread operator allows an iterable to expand in places where 0+ arguments are expected. It is mostly used in variable array where there is more than 1 values are expected.It allows us the privilege to obtain a list of parameters from an array.
    show all the bills from local storage


[ ]Bill list component
    []map method

[ ]editBill function in BillContext.js file
    [ ]filter method 
[ ]alaphabetical ordrer of list in BillContext
    []sort method
##################################### next  #####################################
[ ]BillTotal component
    []reduce method
        []accumulator
        []value
    
The accumulator accumulates callback's return values. It is the accumulated value previously returned in the last invocation of the callback—or initialValue, if it was supplied (see below).
currentValue
The current element being processed in the array.

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/reduce

[v]The span tag is used to group inline-elements in a document. 
    
##################################### next  #####################################

##################################### next  #####################################

##################################### next  #####################################


Creating and nesting components. React apps are made of components. Component is a piece of UI that has its own logic and appearance.Component can be small button or as large
as the entire page. 

React components are JavaScript functons that return  markup. 

functon MyButton() {
    return (
        <button>My button</button>       This is button declaration.... 
    );
}


export default functon MyButton() {
    return(
        <div>
            <h1>My React App</h1>           Nesting MyButton into another Component.
            <MyButton />
        </div>
    );
}


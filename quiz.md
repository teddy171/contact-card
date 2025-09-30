1. What do props help us accomplish?
We can make the conponents reuseable.
✅


2. How do you pass a prop into a component?
like <Component whateverprop="whatever value">
✅


3. Can I pass a custom prop (e.g. `blahblahblah={true}`) to a native
   DOM element? (e.g. <div blahblahblah={true}>) Why or why not?
No. div don't have property blah......
✅


4. How do I receive props in a component?
function Navbar() {
    return (
        <header>
            ...
        </header>
    )
}

add props to the paragmeter.
✅

5. What data type is `props` when the component receives it?
JavaScript object.
✅
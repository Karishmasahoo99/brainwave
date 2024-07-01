useLocation from "react-router-dom" helps us to know which link is clicked 

const pathname=useLocation(). It will give us location about which url we are currently on. In classname we can write (item.url===pathname.hash) and set the color on it when we are on that link.

npm i screen-lock: This disables/enables scrolling.

Scroll-parallax is used for giving us that code generation on right and other one in the right.

Suppose we are using map function to loop over the data, so now, we can give different styling to odd or even elements via:
className="even:py-9 odd:py-3"
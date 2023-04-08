# Helen Lin's Page
![Panda Picture](indexPageImages/panda.webp)

## Table of Contents
- [Helen Lin's Page](#helen-lins-page)
  - [Table of Contents](#table-of-contents)
  - [About Me As A Person](#about-me-as-a-person)
    - [Background](#background)
    - [Favorite Quote](#favorite-quote)
    - [Hobbies](#hobbies)
  - [About Me as a Programmer](#about-me-as-a-programmer)
    - [Education](#education)
      - [Relevant Classes Taken at UCSD](#relevant-classes-taken-at-ucsd)
    - [Experience](#experience)

## About Me As A Person
### Background
Hello! I am **Helen Lin**. I am a student at UCSD studying Mathematics-Computer Science. I am from Irvine, California <sub>but also South Africa</sub>

### Favorite Quote
> Don't say you can't until you prove you can't -Les Paul

### Hobbies
In my free time, I like to cook and bake and do ocasional arts and crafts. 

Somethings that I have baked before are (~~Images not from the internet~~)
* [Matcha Red Bean Bread](https://youtu.be/hKtKUd1-6b0)
  ![Picture of Bread](indexPageImages/Matcha%20Bread.jpg)
* [Cinnamon Rolls](https://www.youtube.com/watch?v=HjOqNLDf-Cg)
  ![Picture of Cinnamon Rolls](indexPageImages/Cinnamon%20Roll.jpg)
* Sweet Rice Cakes
  ![Picture of Rice Cakes](indexPageImages/Rice%20Cake.jpg)



## About Me as a Programmer

### Education
Pursuing a B.S. in Mathematics-Computer Science

#### Relevant Classes Taken at UCSD
- [x] CSE 11: Introduction to Programming and Computeational Problem-Solving
- [x] CSE 12: Basic Data Structures and Object-Oriented Design
- [x] CSE 15L: Software Tools and Techniques Laboratory
- [x] CSE 30: Computer Organization and Systems Programming
- [x] CSE 100: Advanced Data Structures
- [x] CSE 101: Design and Analysis of Algorithms
- [ ] CSE 105: Theory of Computability (In Progress)
- [ ] CSE 110: Software Engineering (In Progress)

### Experience
* Developer on Triton Software Engineering

  Triton Software Engineering is a organization that design and develop software pro-bono to nonprofit organizations.
  
  Projects:

  1. [San Diego Taxpayers Association Visualization Website](https://github.com/TritonSE/SDCTA-Data-Visualization-Website)
      
       * Data Visualization Website of the data that the client wants to provide to their customers
       * Section of Code I wrote: ([Original File](https://github.com/TritonSE/SDCTA-Data-Visualization-Website/blob/main/SDCTA/src/components/Navbar/NavbarLogin.tsx))
```
import { NavLink, useNavigate } from "react-router-dom";
import "./Navbar.css";

export const NavbarLogin: React.FC = () => {
  const navigate = useNavigate();
  return (
    <div>
      <NavLink to="/Login" className="links" id="login">
        Login
      </NavLink>
      <button
        className="navbar-button"
        id="sign-up"
        onClick={() => {
          navigate("/Signup");
        }}
      >
        Sign Up
      </button>
    </div>
  );
};
```
  2. [Y Stem and Chess Mobile Application](https://github.com/TritonSE/YSC-Mobile-Application)
       * Mobile Application that allows students of the client organization to play chess with each other. 

To get back where you came from (ReadMe file) [click here](README.md)

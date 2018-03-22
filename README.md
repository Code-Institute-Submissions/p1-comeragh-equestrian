# Milestone Project - Comeragh Equestrian

*Developer: sarahloh*

- [Project Brief](#project-brief)
- [Technologies](#technologies-and-dependencies)
- [UXD](#uxd)
- [Wireframes](#wireframes)
- [Github Pages](#deployed-to-github-pages)
- [Tests and Fixes](#tests-and-fixes)

### Project Brief

In this project, you’ll be building a frontend-only website using the technologies that you have learned throughout User Centric Frontend Development.

Build a static (front-end only) website for an equestrian centre - Comeragh Equestrian. As a starting point, you may want to use wireframes, as we did in the UX lesson (you can use Balsamiq or any other tool, including just pen and paper).

The equestrian centre has been in business for over 20 years. You have been given the following requirements after interviews with the client’s representatives:

- Their primary target audience are adults in the surrounding area interested in riding lessons for themselves or their children.

- Also, they would like to use the site to showcase their facilities, staff and activities (camps / treks).

- In addition, they are in the process of creating a social media presence and would like to add links to their Facebook, Twitter, YouTube and Instagram pages. 


### Technologies and Dependencies

- [HTML5](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5)
- [CSS3](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS3)
- [Bootstrap v3.3.7](https://getbootstrap.com/docs/3.3/)
- - https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css
- - https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js
- [Font Awesome v4.7.0](https://fontawesome.com/v4.7.0/)
- - https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css
- [jQuery v3.3.1](https://jquery.com)
- - https://code.jquery.com/jquery-3.3.1.min.js



### UXD

| Strategy  | Focus                                                       | User Needs                                                                                        | Business Objectives                                                                             |
|-----------|-------------------------------------------------------------|---------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------|
|           | What are you aiming to achieve?                             | I’m interested in keeping a horse and want to find out more about the yard’s facilities and costs | Increase clients - B2C                                                                          |
|           |                                                             | I want to buy a horse                                                                             | Social currency                                                                                 |
|           | For whom?                                                   | I want to book riding lessons for myself / my child/ group                                        | Increase brand awareness                                                                        |
|           | TARGET AUDIENCE                                             | I want to see photos / videos of the yard / horses / treks / trails / hunts                       | ~~Advertise job opportunities~~                                                                 |
|           |                                                             | I want to read about the staff/trainers                                                           |                                                                                                 |
|           |                                                             | I want to find out about pony camp dates / cost for my child during holidays                      |                                                                                                 |
|           |                                                             | I’m looking for address / contact information                                                     |                                                                                                 |
|           |                                                             | I want to see what classes run and on which days                                                  |                                                                                                 |
|           |                                                             | I want to send a message to the yard manager                                                      |                                                                                                 |                    

| Scope     | Focus                                                       | Functional Specification                                                                          | Content Requirements                                                                            |
|-----------|-------------------------------------------------------------|---------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------|
|           | Which features?                                             | About                                                                                             | Send a message                                                                                  |                    
|           | What’s on the table?                                        | Contact                                                                                           | Access links to social media                                                                    |                    
|           |                                                             | Social                                                                                            | Read about the team                                                                             |                    
|           |                                                             | Livery                                                                                            | Access phone number                                                                             |                   
|           |                                                             | Team                                                                                              | Access location                                                                                 |                    
|           |                                                             | Gallery                                                                                           | Read about pony camps (dates / cost / activities)                                               |                    
|           |                                                             | Pony Camp                                                                                         | Read about riding lessons / treks / trails (dates / cost / groups / individual / adult / child) |                   
|           |                                                             | Riding Lessons                                                                                    | Read about the livery facilities at the yard                                                    |                   
|           |                                                             | ~~Work With Us~~                                                                                  | View photo gallery / videos                                                                     |                    
|           |                                                             |                                                                                                   | ~~View and apply for a job~~                                                                    |                    
|           |                                                             |                                                                                                   | ~~Book a lesson / trek using online calendar~~                                                  |                    

| Structure | Focus                                                       | Interaction Design                                                                                | Information Architecture                                                                        |                    
|-----------|-------------------------------------------------------------|---------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------|
|           | How is the information structured?                          | Where am I? / How did I get here? / What can I do here? / Where can I go?                         | Organizational / Navigational schemas (tree / nested list / hub and spoke / dashboard)          |                    
|           |                                                             |                                                                                                   | HOME                                                                                            |                    
|           | How is it logically grouped?                                | Mobile - hamburger navigation                                                                     | About - Welcome / Lessons / Livery                                                              |                    
|           |                                                             | Desktop - fixed navbar                                                                            | Livery                                                                                          |                    
|           |                                                             |                                                                                                   | Camps & Lessons - Pony Camp / Lessons / Treks / Trails                                          |
|           |                                                             |                                                                                                   | Gallery - Photo Albums / Videos                                                                 |                    
|           |                                                             |                                                                                                   | Contact - Phone / Location / Message                                                            |

| Skeleton  | Focus                                                       | Interface Design                                                                                  | Navigational Design |                                                      | Information Design |
|-----------|-------------------------------------------------------------|---------------------------------------------------------------------------------------------------|---------------------|------------------------------------------------------|--------------------|
|           | How will the information be represented?                    | See wireframes                                                                                    | HOME                |                                                      |                    |
|           |                                                             |                                                                                                   | About               |                                                      |                    |
|           | How will the user navigate to the information and features? | Mobile - contact / location / social at bottom of nav                                             | Livery              |                                                      |                    |
|           |                                                             |                                                                                                   | Camps & Lessons >   | Pony Camp                                            |                    |
|           |                                                             |                                                                                                   |                     | Riding Lessons                                       |                    |
|           |                                                             |                                                                                                   | Gallery             |                                                      |                    |
|           |                                                             |                                                                                                   | Contact             |                                                      |                    |

| Surface   | Focus                                                       | Visual Design                                                                                                                                                                                                                         
|-----------|-------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------|
|           | What will the finished product look like?                   | Fonts: @import url('https://fonts.googleapis.com/css?family=Poppins:300&#124;Roboto:300,400');                            |
|           |                                                             | 2b2118                                                                                                               |
|           | What colours, typography and design elements will be used?  | 894334                                                                                                               |
|           |                                                             | f7f4e5                                                                                                               |
|           |                                                             |                                                                                                                      |                    

#### Wireframes

![Mobile Wireframes](http://bit.ly/2Fx7Pdd)

![Mobile Wireframes](http://bit.ly/2oWn6Kx)


### Deployed to Github Pages
[https://sarahloh.github.io/p1-comeragh-equestrian/](https://sarahloh.github.io/p1-comeragh-equestrian/)

### Tests and Fixes

[**HTML Validator Results**](https://validator.w3.org/nu/?doc=https%3A%2F%2Fsarahloh.github.io%2Fp1-comeragh-equestrian%2F)

[**CSS Validator Results**](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fsarahloh.github.io%2Fp1-comeragh-equestrian%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)

#### *Mobile*

Tested on iPhone 5 & 6

---

**PROBLEM**

Nav toggle off screen on mobile simulator but not on narrow chrome window

**FIX** 

Removed negative margin from .container-fluid>.navbar-collapse

---

**PROBLEM**

List-default li wrap not indenting

**FIX**

Wrapped li text in span and set icon width:20%

```css
.list-default i {
    display: inline-block;
    width: 20%;
    text-align: center;
    padding-right: 10px;
}

.list-default .list-item-text {
    display: inline-block;
    width: 80%;
    vertical-align: top;
}
```

---

#### *Tablet*

Tested on iPad simulator (Chrome)

---

**PROBLEM**

Nav toggle off screen

**FIX**

Change margin-left to padding-left

```css
.nav-links {
    padding-left: 60px;
}
```

---

#### *Desktop*

Tested on Chrome, Safari, Firefox

---

**PROBLEM**

Gallery column md wrapping but leaving gaps

**FIX**

Added rows around columns

---


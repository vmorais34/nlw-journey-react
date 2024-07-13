# Project developed in the event NLW Journey by Rocketseat 🚀

- init: 11.07
- Vinicius Morais

[Figma](/)
[Github](https://github.com/rocketseat-education/nlw-journey-react)
[Linkedin](https://www.linkedin.com/in/vinicius-santos-de-morais/)
[Doc-BackEnd](https://nlw-journey.apidocumentation.com/reference)

## How to Run

- npm i on the root file
- npm run dev

## to do

- [x] - Clonar
 - [x] - Primeira Aula
- [ ] - Subir Prod no Github


- Lesson 2

npm i react-router-dom

### React Router

[Doc](https://reactrouter.com)

- **Name of the folder inside the folder pages is the link in the URL**
-  Following the doc, we setup the enviroment changing the main file app.tsx with the component of the library required to make the pages work.
- Then, on the element prop we pass the component for the page. Very easy to use and create others.

{
  path: "/",
  component: <CreateTripPage />
}

- we can create 404 Page


**We have 2 ways to navigate our user**

 - By a link
 - By any callBack (16:20)
  - Navigate Function - useNavigate()


-- we start to separe the components in 18:30 by significated
 - we started here this time
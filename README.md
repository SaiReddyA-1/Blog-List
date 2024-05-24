# Blog List Application

This project involves building a **Blog List** application using React. The goal is to apply various React concepts such as component creation, state management, and routing.

## Project Overview

The Blog List application displays user information and a list of blogs. The application is designed to be responsive, adapting to different screen sizes.

### Design References

- **Extra Small (Size < 576px), Small (Size >= 576px), Medium (Size >= 768px)**  
  ![Small and Medium Screens](https://assets.ccbp.in/frontend/content/react-js/routing-practice-blog-list-sm-output-v2.png)
  
- **Large (Size >= 992px) and Extra Large (Size >= 1200px)**  
  ![Large and Extra Large Screens](https://assets.ccbp.in/frontend/content/react-js/routing-practice-blog-list-lg-output.png)

### Components Structure

![Components Structure](https://assets.ccbp.in/frontend/content/react-js/routing-practice-blog-list-component-breakdown-structure.png)

## Set Up Instructions

1. Clone the repository.
2. Navigate to the project directory.
3. Install dependencies by running `npm install`.
4. Start the application using `npm start`.

## Functionality

The application has the following functionalities:

- Displays user information and a list of blogs on the Home Route.
- The `Home` component receives a `blogsList` prop containing a list of blog objects. Each blog object includes the following properties:
  - `id`: Number
  - `title`: String
  - `description`: String
  - `publishedDate`: String

### Routes

- The `Home` route corresponds to `/`.
- The `About` route corresponds to `/about`.
- The `Contact` route corresponds to `/contact`.

## Implementation Files

Below are the files and components used in this project:

- `src/components/Home/index.js`
- `src/components/BlogList/index.js`
- `src/components/BlogList/index.css`
- `src/components/BlogItem/index.js`
- `src/components/BlogItem/index.css`
- `src/components/UserInfo/index.js`
- `src/components/UserInfo/index.css`

### Components Description

1. **Home Component (`Home/index.js`)**
   - This component renders the `UserInfo` and `BlogList` components.
   - It receives a `blogsList` prop which is passed down to the `BlogList` component.

2. **BlogList Component (`BlogList/index.js` and `BlogList/index.css`)**
   - This component maps through the `blogsList` and renders a `BlogItem` for each blog.

3. **BlogItem Component (`BlogItem/index.js` and `BlogItem/index.css`)**
   - This component displays individual blog details such as title, description, and published date.

4. **UserInfo Component (`UserInfo/index.js` and `UserInfo/index.css`)**
   - This component displays user information including a profile image and user details.

## Resources

### Image URLs

- [Profile Image](https://assets.ccbp.in/frontend/react-js/profile-img.png) (alt text: "profile")

### Colors

- ![#9aa5b1](https://via.placeholder.com/15/9aa5b1/000000?text=+) `#9aa5b1`
- ![#616e7c](https://via.placeholder.com/15/616e7c/000000?text=+) `#616e7c`
- ![#12022f](https://via.placeholder.com/15/12022f/000000?text=+) `#12022f`

### Font Families

- Roboto

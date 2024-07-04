 
# Student Management Web Application

This project demonstrates a  web application for managing student records with CRUD operations. It utilizes Django REST Framework for the backend API and React JS for the frontend user interface.

## Preview

 ![image](https://github.com/freda1874/Django-RESTFramework-Web-App/assets/85437054/7108d6c4-abd5-49e1-b90c-089b2be9bd2f)

## Application Architecture

The application follows a typical client-server architecture where:
- **Client**: React JS frontend for user interaction
- **Server**: Django backend using Django REST Framework for data management

## Steps to Develop the Application

### Backend Development

1. **Setup**
   - Install Python and Django.
   - Create a new Django project and set up a virtual environment.

2. **Create Django App**
   - Define models for student data.
   - Generate migrations and apply them to create database tables.
   - Set up Django admin for managing student records.

3. **Implement REST API**
   - Develop serializers to convert model instances to JSON.
   - Create views using Django REST Framework's `APIView` for handling CRUD operations.
   - Configure URLs to map API endpoints to views.

### Frontend Development

1. **Create React App**
   - Install Node.js and create a new React app using `create-react-app`.
   - Set up necessary dependencies like Axios for API calls.

2. **Build Components**
   - Design components for navigation, student list, forms (add/update student), etc.
   - Use React hooks and state management to handle component logic and data flow.

3. **Integrate with Backend**
   - Connect React components to Django REST API endpoints using Axios.
   - Implement CRUD operations in React components to interact with the backend.

## Testing CRUD Operations

- Use tools like Postman or Django REST Client to test API endpoints.
- Test frontend functionality by adding, updating, and deleting student records.

  Happy coding! 🚀

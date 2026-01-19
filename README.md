# yszne-pl-ii

Food Ordering System  
Software Development Methodologies Project

## Description
This project is a Food Ordering System developed as part of the Software Development Methodologies course.  
It is implemented as a RESTful API using FastAPI and demonstrates a simple layered architecture along with unit testing using pytest.

## Features
- User authentication (login)
- List available food items
- Cart operations (add items, view cart, clear cart)
- Order creation and order listing
- RESTful API with Swagger documentation

## Technologies Used
- Python
- FastAPI
- Pytest
- Uvicorn

## API Endpoints (Swagger)
After running the project, the Swagger UI is available at:  
http://127.0.0.1:8000/docs

Main endpoints:
- `POST /login` – User authentication
- `GET /foods` – List food items
- `POST /cart/items` – Add item to cart
- `GET /cart` – View cart
- `DELETE /cart` – Clear cart
- `POST /orders` – Create order
- `GET /orders` – List orders
- `GET /` – Root / health check

## Project Structure


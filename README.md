
# Campus Manager API

A simple and fast REST API for managing campus courses, built with Node.js and Express.

Live API: https://peisntech.github.io/campus-manager-api/

## 🚀 Features
- Get all courses
- Get course by ID
- Add new course
- Update course
- Delete course
- Fast, lightweight Express server

## 🛠️ Tech Stack
- Node.js
- Express.js

## 📦 Installation

##bash✅
git clone https://github.com/Peisntech/campus-manager-api.git
cd campus-manager-api
npm install
npm start

 📚 API Endpoints

| Method | Route | Description | Example |
| :--- | :--- | :--- | :--- |
| GET | `/` | Welcome message | Returns hello |
| GET | `/api/courses` | Get all courses | List of courses |
| GET | `/api/courses/:id` | Get single course | `{id: 1}` |
| POST | `/api/courses` | Add new course | `{name: "CS"}` |
| PUT | `/api/courses/:id` | Update a course | Update by ID |
| DELETE | `/api/courses/:id` | Delete a course | Delete by ID |

## 📦 Courses Data Structure

| Field | Type | Description |
| :--- | :--- | :--- |
| `id` | Number | Unique ID of course |
| `name` | String | Name of the course |
| `code` | String | Course code e.g. CS101 |
| `credits` | Number | Number of credits |



##Author 
Nsubuga Pius🦺
piusnsubuga86@gmail.com

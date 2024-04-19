How to Use videoapp task:
1.Setting Up:
Ensure Django and DRF are properly installed in your environment.
Clone the repository and navigate to the project directory.
2.Database Setup:
Run migrations to set up the database: python manage.py migrate.
Running the Server:
Start the Django development server: python manage.py runserver.
3.API Endpoints:
Access video-related APIs at /api/videos/.
Ensure proper authentication by including a valid token in the Authorization header (Token <token>).
4.Testing:
Execute tests to validate API functionality:
bash
Copy code
python manage.py test
Endpoints and Operations:
Use HTTP methods (GET, POST, PUT, DELETE) to interact with the /api/videos/ endpoint.
Examples:
GET /api/videos/: Retrieve all videos.
POST /api/videos/: Create a new video by providing name and video_url in the request data.
PUT /api/videos/<video_id>/: Update an existing video by ID.
DELETE /api/videos/<video_id>/: Delete a video by ID.
Important Notes:
Replace <video_id> with the actual ID of the video for update and delete operations.
Ensure proper token authentication (Token <token>) for authorized access to protected endpoints.

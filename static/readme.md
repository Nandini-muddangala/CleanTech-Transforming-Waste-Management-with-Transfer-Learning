The application accepts image inputs through a web interface where users can upload photos of waste materials. Uploaded images are temporarily stored in the static/uploads directory on the server. Once an image is uploaded, it is automatically processed by the pre-trained VGG16 model, which classifies it into one of three categories: biodegradable, recyclable, or trash. The classification result is then displayed on the web page along with the uploaded image, providing users with immediate feedback. This setup enables real-time, user-friendly waste classification suitable for deployment in eco-friendly systems or educational platforms.

Here's just the structure of the static/uploads folder:

static/
└── uploads/
    ├── image1.jpg
    ├── image2.png
    ├── test_waste.jpg
    └── ... (more uploaded images)

Smart Health-Aware Shopping Cart

Overview:
The Smart Health-Aware Shopping Cart is an AI-powered system designed to promote healthy shopping habits. 
It integrates Google Teachable Machine and TensorFlow.js to identify grocery items in real time, classify them as healthy, unhealthy, or neutral, 
and calculate a dynamic health score for the cart. The goal is to assist users in making informed choices while shopping.

Key Features:
- Real-time item detection through webcam.
- AI-powered classification using Teachable Machine & TensorFlow.js.
- Automatic health score calculation for the shopping cart.
- Categorization of items into healthy, unhealthy, and neutral groups.
- Live cart view with healthy/unhealthy counters.
- Clean and responsive user interface.

Technology Stack:
- Frontend: HTML, CSS, JavaScript.
- AI Frameworks: TensorFlow.js, Teachable Machine.
- Supporting Libraries: @tensorflow/tfjs, @teachablemachine/image.

Working Mechanism:
1. A pre-trained AI model from Teachable Machine is loaded.
2. The system activates the webcam and scans items.
3. The AI model predicts the item label with a confidence score.
4. Items are categorized and added to the cart dynamically.
5. The sidebar updates the cart health score, total item count, and healthy/unhealthy breakdown.

Project Structure:
📁 Smart Health Cart
 ┣ 📄 index.html   # Main project file with integrated HTML, CSS, and JS.
 ┣ 📄 README.md    # Documentation for GitHub repository.
 ┗ 📁 assets/      # Optional folder for images, demo GIFs, or media files.

Future Improvements:
- Expanding the dataset to include more grocery items.
- Integrating nutrition information for each detected item.
- Connecting with e-commerce or shopping apps to suggest healthier alternatives.
- Adding mobile app integration for on-the-go use.

Conclusion:
The Smart Health-Aware Shopping Cart combines artificial intelligence with real-time detection to support users in making healthier shopping choices. 
By analyzing the nutritional value of grocery items and providing instant feedback, it encourages balanced shopping habits and promotes a healthier lifestyle.

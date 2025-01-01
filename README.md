# Project Title

# AI-based Plant Identifier

# Summary
summary = """
The idea is to create an AI app that can identify plants by analyzing pictures taken by the user. 
The app will help people who love nature and gardening by gathering information about the plants in their surroundings faster.
"""

# Background
background = """
Many people who spend their time in nature are curious about the plants they encounter. 
With the help of this AI app, a single picture can answer questions about which plant it is and how to take care of it, 
thereby improving knowledge of biological diversity. This would also prevent people from interacting with dangerous or toxic plants, 
decreasing the number of poisonings caused by plants. 

This idea inspires me because I am a nature lover, and on my walks, I often encounter plants I don't recognize. 
Searching manually for plant information can be time-consuming, and this app would simplify that process.
"""

# How is it used?
usage = """
The app can be used during walks or when discovering unknown plants. It is primarily intended for gardeners, 
nature lovers, and students conducting research or writing projects involving plants. 

The app works by taking a picture of a plant using a mobile camera, allowing the AI to analyze the image and compare it 
to a plant species database. After analysis, the app provides information about the plant, including its name, 
maintenance, and useful facts.
"""

# Image Examples
image1 = "https://www.freepik.com/free-vector/plant-pot-cartoon_28881307.htm"
image2 = "https://www.freepik.com/premium-vector/green-plant-red-pot-3d-icon-houseplant-potted-plant-flower-home-garden-3d-vector-illustration-white-background-gardening-nature-decoration-botany-concept_42332064.htm"


# Data Sources and AI Methods
data_sources = [
    "https://plants.usda.gov/",
    "https://garden.org/plants/",
    "https://wfoplantlist.org/"
]

ai_methods = """
The AI model will use convolutional neural networks (CNNs) trained on image datasets of plants. 
Transfer learning from models such as MobileNet or ResNet can be utilized to improve accuracy with limited data.
"""

# Challenges
challenges = """
A key challenge is distinguishing between visually similar plants, which can lead to incorrect identifications. 
Overcoming this requires extensive training data with images from multiple angles, lighting conditions, and growth stages. 
Collecting such a large and diverse dataset is challenging but essential to improve the app's reliability.
"""

# Next Steps
next_steps = """
To enhance the app further, a crowdsourcing feature can be added. This would allow users to contribute their own 
plant pictures, expanding the database. By utilizing community contributions, the app can improve identification 
accuracy and reduce errors over time.
"""

# Acknowledgments
acknowledgments = [
    "https://identify.plantnet.org/sv",
    "https://plant.id/"
]

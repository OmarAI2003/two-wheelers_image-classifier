# two-wheelers_image-classifier Scones Unlimited
## Project Overview

Scones Unlimited, a scone-delivery-focused logistics company, aims to optimize delivery operations using an image classification model. This model identifies delivery vehicles (bicycles and motorcycles) to route drivers efficiently, enhancing operational efficiency.

## Technologies Used

- **AWS Sagemaker**: Building and deploying the image classification model
- **AWS Lambda**: Creating supporting services
- **AWS Step Functions**: Composing an event-driven application
- **Python**: Scripting and model development
- **Jupyter Notebooks**: Data exploration and model training

## Project Steps

### 1. Data Staging
Prepare and upload the training and testing datasets to an S3 bucket. The datasets contain images of bicycles and motorcycles.

### 2. Model Training and Deployment
Use AWS Sagemaker to explore the data, train the image classification model, and deploy the trained model.

### 3. Lambdas and Step Function Workflow
Create AWS Lambda functions to preprocess input data and perform model inference. Define the Step Functions workflow to integrate these services.

### 4. Testing and Evaluation
Test the deployed model and evaluate its performance using a set of validation images.

### 5. Optional Challenge
Implement additional features or improvements to the model or workflow as per the optional challenge guidelines.

### 6. Cleanup Cloud Resources
Ensure all AWS resources created during the project are properly cleaned up to avoid unnecessary charges.

## Getting Started

### Prerequisites
- AWS Account
- Python 3.7+
- AWS CLI
- Git

### Installation
1. Clone the repository:
   - `git clone https://github.com/yourusername/scones-unlimited-image-classification.git`
   - `cd scones-unlimited-image-classification`
2. Install dependencies:
   - `pip install -r requirements.txt`
3. Configure AWS CLI:
   - `aws configure`

## Project Structure

- **data/**: Contains training and testing datasets
- **notebooks/**: Jupyter notebooks for data exploration and model training
- **src/**: Lambda functions and Step Function workflow definitions
- **models/**: Trained model files
- **README.md**: Project documentation
- **requirements.txt**: Project dependencies

## Results
The image classification model successfully distinguishes between bicycles and motorcycles, aiding Scones Unlimited in optimizing delivery operations by routing drivers based on their vehicle type.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any changes or improvements.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements
- The team at Scones Unlimited
- AWS for providing the cloud infrastructure
- The open-source community for various tools and libraries

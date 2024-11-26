# AWS Certified Cloud Practitioner Notes: Internet of Things (IoT) Services

This section covers essential AWS services designed to support Internet of Things (IoT) applications, enabling secure communication and management of IoT devices.

## 🌐 Internet of Things (IoT) Services

### 1. AWS IoT Core
- **Purpose**: A fully managed cloud service that enables connected devices to easily and securely interact with cloud applications and other devices.

#### Key Features:
- Supports secure device connectivity and management.
- Provides message routing and processing capabilities.
- Integrates with AWS services for data analytics, storage, and machine learning.

#### Real-Life Example:
A smart agriculture company uses AWS IoT Core to connect sensors in the field that monitor soil moisture and weather conditions. The data collected is sent to the cloud for analysis, allowing farmers to make informed decisions about irrigation and crop management.

---

### 2. AWS IoT Greengrass
- **Purpose**: A service that extends AWS functionality to edge devices, enabling them to act locally on the data they generate while still using the cloud for management, analytics, and storage.

#### Key Features:
- Enables local execution of AWS Lambda functions on connected devices.
- Supports device messaging and data management at the edge.
- Allows for secure communication between devices and the cloud.

#### Real-Life Example:
A manufacturing company uses AWS IoT Greengrass to process data from machines on the factory floor. By running analytics locally, they can detect anomalies in real-time and take immediate action, improving operational efficiency and reducing downtime.

---

## 📚 Additional Resources
- [AWS IoT Core Documentation](https://aws.amazon.com/iot-core/)
- [AWS IoT Greengrass Documentation](https://aws.amazon.com/greengrass/)
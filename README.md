# Understand
**Tagline:**_"From Diagnosis to Understanding"_
## Overview

Understand is a platform designed to provide comprehensive resources and community support for individuals diagnosed with various conditions later in life, including neurodiverse conditions, mental health disorders, and significant physical changes, as well as their families. The platform focuses on educating users about their diagnoses, guiding them through the next steps, and connecting them with a supportive community.

## Features
-**Educational Content:** Access in-depth articles, videos, and guides covering a wide range of conditions, focusing on late diagnosis and significant life changes.
-**Community Stories:** Share personal stories, experiences, and challenges related to diagnosis or life changes.
-**Resource Directory:** Discover a curated list of services, organizations, and tools tailored to your specific needs.
-**Discussion Forums:** Connect with others facing similar challenges, share advice, and find support.

## Getting Started
### Prerequisites
-**Node.js**: Ensure you have Node.js installed for the front-end React application.
-**Python**: Install Python for the Django back-end framework.
-**MySQL**: Set up a MySQL database to store user data, resources, and community discussions.

### Installation
1.**Clone the Repository**
```bash
   git clone https://github.com/Morganiron/Understand.git
   cd Understand
   ```
2.**Set Up the Front-End (React)**
```bash
   cd src/frontend
   npm install
   npm start
   ```

   More details can be found in the [Frontend Documentation](src/frontend/README.md).

3.**Set Up the Back-End (Django)**
```bash
   cd src/backend
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   pip install -r requirements.txt
   python manage.py migrate
   python manage.py runserver
   ```

   More details can be found in the [Backend Documentation](src/backend/README.md).

4.**Configure MySQL**
   - Set up your MySQL database and update the Django settings with your database credentials in `src/backend/backend/settings.py`.

### Usage
-**Development Server:**
  - React: Access the front-end at `http://localhost:3000`.
  - Django: Access the back-end API at `http://localhost:8000`.

-**Building for Production:**
```bash
   cd src/frontend
   npm run build
   ```
## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Make your changes and commit (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Create a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For questions or suggestions, please reach out to the project maintainer via [GitHub Issues](https://github.com/Morganiron/Understand/issues).

---

*This project is an ongoing effort, and your contributions and feedback are invaluable to its success. Together, we can create a platform that provides much-needed resources and support for individuals and families navigating the complexities of late-diagnosed conditions and life-changing events.*
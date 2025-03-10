# RubyTestGrid
A scalable, modular test automation framework using **Selenium, Ruby, Appium, and Rest Assured**.


## 📌 Features  
✅ **Hybrid UI & API Testing** – Web (Selenium), Mobile (Appium), API (Rest Assured)  
✅ **Page Object Model (POM)** – Maintainable and reusable UI tests  
✅ **Parallel Execution** – Faster test execution  
✅ **CI/CD Ready** – Easily integrable with Jenkins, GitHub Actions  
✅ **Comprehensive Logging & Reporting**  

## 📂 Folder Structure  
- **config/** → Test settings, environment variables  
- **lib/** → Core framework utilities  
- **pages/** → Page Object Models  
- **tests/ui/** → Selenium & Appium test scripts  
- **tests/api/** → API test cases with Rest Assured  
- **reports/** → Test execution reports  

## 🚀 Installation  
### 1️⃣ Prerequisites  
Ensure **Ruby 3.0+, Bundler, Appium, and Selenium** are installed.

### 2️⃣ Setup & Run  
```sh
git clone https://github.com/yourusername/RubyTestGrid.git
cd RubyTestGrid
bundle install

## Run Test
rake test:ui   # Run UI tests
rake test:api  # Run API tests
rake test:all  # Run all tests

📊 Reports
Test results are saved in the reports/ directory.

🤝 Contributing
Feel free to fork and contribute via pull requests.

MIT License © 2024 RubyTestGrid

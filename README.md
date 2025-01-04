# Internship Listing Platform: Phase 1 Roadmap

## **Project Overview**
This platform aims to list internships by searching the web for specific keywords and displaying accurate results. The primary goal for this phase is to learn and apply regex for data extraction, identify the best algorithm for accuracy, and develop a functional MVP.

---

## **Phase Objectives**
1. Learn and apply **regex** for data extraction and filtering.  
2. Identify and test the best algorithm to fetch and list internships accurately.  
3. Develop a functional MVP (basic setup) for web scraping and listing.  

---

## **Timeline and Milestones**

| **Week** | **Tasks** | **Deliverables** |  
|----------|-----------|------------------|  
| **Week 1** | **Learning Regex Fundamentals**  
- Understand regex basics: patterns, anchors, quantifiers, character classes.  
- Practice extracting simple text data.  
- Build proficiency using online tools like [Regex101](https://regex101.com).  
| - Regex cheatsheet.  
- Practice exercises (extract email, dates, keywords, etc.).  

| **Week 2** | **Advanced Regex & Web Scraping Basics**  
- Learn advanced regex: lookaheads, backreferences, and greedy/lazy matching.  
- Set up web scraping tools (Puppeteer, Cheerio, or Beautiful Soup for Python).  
- Use regex in scraping scripts to extract job titles, companies, and descriptions.  
| - Script to extract data from one website.  
- Test regex on real-world job pages.  

| **Week 3** | **Initial Algorithm Design**  
- Research existing algorithms for data accuracy (e.g., keyword matching, scoring systems).  
- Design a simple scoring system for internship listings (e.g., keyword density).  
- Set up filters to exclude irrelevant listings.  
| - A functional algorithm prototype.  
- Filtered internship listings from test websites.  

| **Week 4** | **Algorithm Testing & Optimization**  
- Test the algorithm on multiple sources.  
- Evaluate accuracy using test cases:  
   - Measure true positives, false positives, and false negatives.  
   - Adjust filters and scoring logic based on results.  
- Optimize regex patterns and logic for better results.  
| - Test reports with accuracy metrics.  
- Refined algorithm with optimized regex patterns.  

| **Week 5** | **Building the MVP**  
- Integrate the scraping algorithm into the platform’s back end.  
- Create a basic front-end interface to display the results.  
- Allow filtering by fields like location or job type.  
| - Working MVP that lists internships.  
- Feedback loop for algorithm improvement.  

---

## **Detailed Tasks**

### **Week 1-2: Learn Regex**
1. **Fundamentals (Day 1-2)**  
   - Learn regex syntax (e.g., `\w`, `\d`, `.*`).  
   - Practice using regex for extracting simple patterns like emails, phone numbers, and URLs.  

2. **Intermediate Regex (Day 3-5)**  
   - Learn groups, alternation (`|`), and modifiers (`+`, `?`, `{n}`).  
   - Test patterns to capture data like dates, keywords, and descriptions.  

3. **Advanced Regex (Day 6-7)**  
   - Explore lookaheads/lookbehinds (`(?=...)`), lazy quantifiers (`*?`), and backreferences (`\1`).  
   - Solve complex scraping problems like extracting only internships from mixed job pages.  

---

### **Week 3: Initial Algorithm Design**
1. **Define Accuracy Metrics**:  
   - **True Positives**: Relevant internships correctly identified.  
   - **False Positives**: Irrelevant listings mistakenly flagged as internships.  
   - **False Negatives**: Missed relevant internships.  

2. **Scoring Logic**:  
   - Assign weights to keywords (e.g., “internship,” “graduate program”).  
   - Filter out irrelevant terms (e.g., “senior,” “executive”).  

3. **Initial Script**:  
   - Write a script to scrape internship data from at least 2 sources.  
   - Test regex patterns to extract relevant fields.  

---

### **Week 4: Algorithm Testing & Optimization**
1. **Testing**:  
   - Use sample test cases to evaluate the algorithm’s accuracy.  
   - Refine regex patterns for edge cases (e.g., job descriptions with mixed keywords).  

2. **Optimization**:  
   - Analyze false positives/negatives and tweak scoring weights.  
   - Add more exclusion keywords and adjust regex patterns.  

3. **Integration with Database**:  
   - Store scraped results in a database for better testing.  
   - Create a simple query system to retrieve listings for analysis.  

---

### **Week 5: MVP Development**
1. **Back-End Integration**:  
   - Connect the scraping algorithm with a simple REST API.  
   - Store internship listings in the database with fields like:  
     - Job Title  
     - Company  
     - Location  
     - Description  

2. **Front-End Interface**:  
   - Display internship results in a clean and responsive UI.  
   - Add filters for location, type, and date posted.  

3. **Feedback Loop**:  
   - Allow users to report inaccuracies in the listings.  
   - Use feedback to refine regex and filters.  

---

## **Tools & Resources**

### **Learning Regex**
- **Regex101**: Interactive regex editor with explanations.  
- **Books/Guides**: *"Regular Expressions Cookbook"* by Goyvaerts and Levithan.  

### **Web Scraping**
- **Puppeteer (Node.js)**: Ideal for dynamic pages.  
- **Cheerio (Node.js)**: Lightweight for static pages.  
- **Beautiful Soup (Python)**: Beginner-friendly library.  

### **Database**
- MongoDB (NoSQL, flexibility for storing unstructured data).  

---

## **Other Material**
Here's some extra stuff I found online:

A github repo with a job scraping codebase:

https://github.com/LorenzoLaCorte/internship-scraper

A YT video with a scraping tutorial for job listings:
https://www.youtube.com/watch?v=zz3YTqDcDO0

A Medium blog post on job scraping:
https://levelup.gitconnected.com/a-web-scraper-for-internships-880861a05f58


---

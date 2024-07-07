# Debt Instrument Data Extraction Using Google Gemini

## Project Overview

Invergence Analytics, a finance industry company based in the USA, employs interns to manually extract information from debt instruments embedded in .vif files. These documents, including promissory notes and debt notes, require interns to identify and record data such as the lender, borrower, loan amount, interest rate, maturity amount, and other relevant details into Google Sheets or Excel files. This manual process is time-consuming, prone to errors, and can be monotonous for interns.

To address these challenges, this project explores the use of Google's Gemini vision model to automate the extraction of relevant information from these documents.

## Problem Statement

Manual data extraction from debt instruments has several drawbacks:
- High time consumption
- Potential for inaccuracies
- Intern boredom and time constraints

## Solution

### Project Highlights
- Utilized Google's Gemini vision model, a multimodal large language model developed by Google DeepMind.
- Automated the extraction of key fields from debt documents.
- Achieved high accuracy for most fields, with room for further enhancements.

### Challenges
- Documents often include handwritten text, various font styles, low transparency, and multiple languages.
- Existing CV models struggled with the diverse and low-quality nature of the documents.

### Google's Gemini Vision Model
- Launched in December 2023, comprising Gemini Ultra, Gemini Pro, Gemini Flash, and Gemini Nano.
- Positioned as a competitor to OpenAI's GPT-4.
- Vision-pro service was used via its API-Key for this project.

## Implementation

### Steps
1. **Data Collection**: Gathered a dataset of debt instrument images.
2. **Model Integration**: Integrated Google's Gemini vision model using the `langchain_google_genai` and `generativeai` libraries.
3. **Prompt Engineering**: Designed prompts to accurately extract required fields.
4. **Data Retrieval**: Structured the retrieval of data to maximize accuracy.
5. **Evaluation**: Assessed the model's performance, achieving accurate extraction for 8-9 out of 10-12 required fields.

### Enhancements
- Adjusting `top_k`, `top_p`, and `temperature` parameters for better model performance.
- Further tuning and model improvements to handle the limitations of the image quality and diversity.

### Libraries Used
- `langchain_google_genai`
- `langchain`
- `google`
- `generativeai`
- `pandas`

## Results and Learnings

Although the project did not reach production-level deployment, it provided valuable insights into the potential of LLMs like Google Gemini to significantly enhance productivity in the finance industry. The experience highlighted the importance of prompt engineering and model tuning in achieving high accuracy in automated data extraction.

## Future Work

Further work can focus on:
- Enhancing the model to handle even more diverse and low-quality document images.
- Integrating the solution into a production environment.
- Exploring other LLMs and vision models for improved performance.

## Conclusion

This project demonstrated the potential of Google's Gemini vision model to automate the tedious task of extracting information from debt instruments, thereby improving accuracy and saving time. The learnings from this project underscore the transformative impact of LLMs on industry productivity.

## Contact

For more information, please contact:
- Name: Mohammed Aftab
- Email: maftab@convergenceinc.com
- Organization: Invergence Analytics

---
![image](https://github.com/Aftabbs/Debt-Instrument-Data-Extraction-Using-Google-Gemini/assets/112916888/672674b0-9475-473e-8dfd-672085613691)

*This project was developed as part of the ongoing efforts at Invergence Analytics to leverage advanced AI technologies for improving operational efficiency and productivity in the finance industry.*
*The images used in this project is a demo pictures found on google*

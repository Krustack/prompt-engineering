# Introduction to Prompt Engineering

## Table of Contents
1. [What is Prompt Engineering?](#what)
2. [Why is Prompt Engineering Important?](#why)
3. [Basic Principles of Prompt Engineering](#principles)
4. [Practical Examples](#examples)
5. [Ask-Before-Answer Prompting](#ask-before-answer)
6.

<a name="what"></a>
## What is Prompt Engineering?

Prompt Engineering หมายถึงกระบวนการทำคำถาม, คำแนะนำ หรือคำประโยคที่ให้เป็นข้อมูลนำเข้าให้กับโมเดล AI เพื่อผลิตผลลัพธ์ที่เฉพาะเจาะจง การสร้าง Prompt เหล่านี้เป็นสิ่งสำคัญในการควบคุมพฤติกรรมของ AI รูปร่างการตอบสนองของมัน และทำให้มันมีประโยชน์.

<a name="why"></a>
## Why is Prompt Engineering Important?

ด้วยการมาของ GPT-3 และ GPT-4 ความสามารถในการสร้างคำตอบที่สอดคล้องและเหมาะสมตามบริบทได้เพิ่มขึ้นอย่างมาก อย่างไรก็ตาม โมเดลเหล่านี้ต้องการคำสั่งที่มีประสิทธิภาพเพื่อแนะนำการตอบสนองของพวกเขา ดังนั้น ศิลปะในการสร้างคำสั่งที่มีประสิทธิภาพ - ที่รู้จักกันในชื่อของ Prompt Engineering - จึงเป็นทักษะที่สำคัญในด้าน AI

<a name="principles"></a>
## Basic Principles of Prompt Engineering

Here are some basic principles to consider when engineering prompts:

1. **ความชัดเจน**: Prompt ควรจะชัดเจนและเฉพาะเจาะจง การสร้าง Prompt ที่คลุมเครืออาจทำให้ได้คำตอบที่ไม่เกี่ยวข้องหรือมีความกำกวม
2. **บริบท**:  ให้บริบทเพียงพอภายใน Prompt นี้สามารถช่วยแนะนำโมเดล AI เพื่อสร้างคำตอบที่ต้องการ
3. **ความยาว**: ความยาวของ Prompt สามารถส่งผลต่อคำตอบ Prompt ที่ยาวขึ้นอาจจำเป็นต้องใช้เพื่อให้บริบทเพียงพอ แต่ Prompt ที่ยาวเกินไปสามารถจำกัดความยาวของคำตอบเนื่องจากขีดจำกัดโทเค็นสูงสุดของโมเดล

<a name="examples"></a>
## Practical Examples

Here are some examples of prompts and their corresponding responses:

- **Prompt**: "Translate the following English text to French: 'Hello, how are you?'"
  - **Expected Response**: "Bonjour, comment ça va?"

- **Prompt**: "Write a brief summary of the novel 'Moby Dick'."
  - **Expected Response**: "Moby Dick is a novel by Herman Melville about the obsessive quest of Ahab, captain of the whaler Pequod, for revenge on a gigantic white sperm whale that on a previous voyage destroyed his ship and severed his leg at the knee."

<a name="ask-before-answer"></a>
## Ask-Before-Answer Prompting

คือเทคนิคการสร้าง Prompt ที่ถามก่อนที่จะตอบ เมื่อคุณเขียนprompt เสร็จเรียบร้อยแล้ว คุณต่อท้ายprompt ไปด้วยประโยค " Before answering, I want you to first ask for any extra information that helps you produce a better answer. If you got no questions, please provide the answer instead " , "What could be improved about your this?" , "Which extra information do you need to give me a better list of advantage" ฯลฯ


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

คือเทคนิคการสร้าง Prompt ที่ถามก่อนที่จะตอบ เมื่อคุณเขียนprompt เสร็จเรียบร้อยแล้ว คุณต่อท้ายprompt ไปด้วยประโยค
**ตามตัวอย่างดังนี้**
1. "Before providing a response, is there any specific context or background information you would like me to consider?"
2. "What are the key criteria or factors that you would like me to take into account while addressing your question?"
3. "Are there any preferences or constraints that you would like me to consider before giving you a recommendation?"
4. "Is there any specific industry or domain you would like me to focus on while discussing the benefits of this solution?"
5. "Before I proceed, would you like me to clarify any terms or concepts related to this topic to ensure a better understanding?"

## การกำหนด ROLE ให้ GPT
1. 👩‍⚕️ Doctor
2. 👨‍🏫 Teacher
3. 👩‍💼 CEO
4. 👮‍♀️ Police Officer
5. 🕵️‍♂️ Detective
6. 👩‍🍳 Chef
7. 👩‍🚀 Astronaut
8. 🎭 Actor
9. 🎨 Artist
10. 📚 Writer
11. 🏋️‍♀️ Fitness Trainer
12. 🎓 Student
13. 🎥 Filmmaker
14. 👩‍🔬 Scientist
15. 🏇 Jockey
16. ⚖️ Lawyer
17. 👨‍🔧 Mechanic
18. 🚒 Firefighter
19. 🎸 Musician
20. 🏊‍♂️ Lifeguard
21. 👩‍⚖️ Judge
22. 🌱 Farmer
23. 🚚 Truck Driver
24. 🏫 Principal
25. 🏥 Nurse
26. 🧑‍🍳 Sous Chef
27. 📷 Photographer
28. 🎤 Singer
29. 🎹 Pianist
30. 🏢 Office Manager
31. 🏨 Hotel Receptionist
32. 🏭 Factory Worker
33. 🚀 Engineer
34. 👷‍♀️ Construction Worker
35. 🧑‍🚒 Paramedic
36. 🧑‍💻 Software Developer
37. 📺 News Anchor
38. 🎭 Theater Director
39. 📝 Journalist
40. 🏡 Realtor
41. 🏢 Accountant
42. 🏥 Surgeon
43. 🎯 Sales Representative
44. 📚 Librarian
45. 🎬 Film Director
46. 🎮 Game Developer
47. 🌍 Tour Guide
48. 🎓 Professor
49. 🧑‍✈️ Pilot
50. 🎁 Gift Shop Attendant
## target audience Examples
1. 🧑‍💻 Programmers
2. 🧒 Students
3. 👩‍👦‍👦 Mothers
4. 🏋️ Fitness enthusiasts
5. 🎮 Gamers
6. 📚 Book lovers
7. 🎓 Professionals
8. 🎯 Small business owners
9. 🎵 Music lovers
10. 🌍 Travel enthusiasts
11. 🚀 Tech-savvy individuals
12. 👵 Senior citizens
13. 🌱 Environmental activists
14. 🎭 Theater enthusiasts
15. 🎨 Artists and creatives
16. 🚴‍♂️ Cycling enthusiasts
17. 🍽️ Foodies and gourmet enthusiasts
18. 💼 Corporate professionals
19. 🤝 Non-profit organizations
20. 🏡 Homeowners or property owners
21. 🎉 Party planners and event organizers
22. ⚽ Sports fans
23. 🚗 Automotive enthusiasts
24. 📸 Photography enthusiasts
25. 🌿 Wellness and health-conscious individuals
26. 🏫 Teachers and educators
27. 🧘‍♀️ Yoga and mindfulness practitioners
28. 🎓 College graduates or alumni
29. 💻 Tech startups
30. 📱 Mobile app users
31. 🎧 Audiophiles
32. 👶 New parents
33. 🌮 Food truck enthusiasts
34. 👥 Social media influencers
35. 👩‍⚕️ Healthcare professionals
36. 🧩 Puzzle and brainteaser lovers
37. 🎭 Community theater groups
38. 🎮 E-sports enthusiasts
39. 🍷 Wine connoisseurs
40. 📝 Writers and authors
41. 🏋️‍♀️ Fitness trainers
42. 🚁 Drone enthusiasts
43. 🐶 Pet owners
44. 🏕️ Outdoor adventurers
45. 👨‍👩‍👧‍👦 Families with young children
46. 🎓 Continuing education seekers
47. 👗 Fashionistas
48. 🎙️ Podcast listeners
49. 🚀 Space exploration enthusiasts
50. 🎬 Film and cinema lovers

    
## example tone
1. 😄 Joyful
2. 😊 Friendly
3. 🤗 Warm
4. 🙌 Encouraging
5. 👍 Positive
6. 😎 Cool
7. 🤩 Excited
8. 🥰 Affectionate
9. 😁 Playful
10. 🎉 Celebratory
11. 🤔 Thoughtful
12. 🌟 Inspirational
13. 🎭 Dramatic
14. 🙏 Grateful
15. 😌 Calm
16. 💪 Assertive
17. 🤝 Supportive
18. 😃 Energetic
19. 😔 Sympathetic
20. 😅 Humorous
21. 😮 Surprised
22. 😢 Sad
23. 🤯 Shocked
24. 😡 Angry
25. 😕 Confused
26. 🤫 Mysterious
27. 🤗 Welcoming
28. 😇 Genuine
29. 🙃 Sarcastic
30. 😂 Funny
31. 🥳 Festive
32. 😤 Frustrated
33. 😓 Apologetic
34. 😬 Awkward
35. 😲 Astonished
36. 🥺 Pleading
37. 😏 Sly
38. 😱 Fearful
39. 😶 Speechless
40. 😵 Stunned
41. 😐 Neutral
42. 🤔 Curious
43. 😴 Sleepy
44. 😠 Irritated
45. 😖 Anxious
46. 😟 Worried
47. 😣 Disappointed
48. 😶 Indifferent
49. 😈 Mischievous
50. 😅 Relieved

## style example
1. 📝 Formal
2. ✒️ Professional
3. 🎩 Sophisticated
4. 💼 Business
5. 🎓 Academic
6. 🖋️ Elegant
7. 📖 Literary
8. 🎥 Cinematic
9. 🎨 Artistic
10. 🌟 Glamorous
11. 📷 Photographic
12. 🎭 Theatrical
13. 🎵 Musical
14. 🌈 Colorful
15. 🕶️ Trendy
16. 🧥 Fashionable
17. 🌿 Natural
18. 🏄‍♂️ Casual
19. 🎸 Rock and Roll
20. 🌺 Bohemian
21. 💥 Edgy
22. 🎬 Retro
23. 🍂 Vintage
24. 🎀 Whimsical
25. 🎢 Playful
26. 🏝️ Tropical
27. 🎉 Festive
28. 🏔️ Adventure
29. 🌌 Sci-Fi
30. 🚀 Futuristic
31. 🌹 Romantic
32. 🌃 Urban
33. 🗺️ Wanderlust
34. 🧪 Experimental
35. 🧘‍♀️ Mindful
36. 🏰 Fairy Tale
37. 📚 Classic
38. 🌻 Rustic
39. 🍕 Casual
40. 🧘‍♂️ Zen
41. 🌸 Minimalistic
42. 🚗 Retro
43. 🎡 Whirlwind
44. 🌅 Serene
45. 🍭 Sweet
46. 🏞️ Scenic
47. 🌊 Oceanic
48. 🍃 Organic
49. 🏛️ Historical
50. 🍿 Popcorn




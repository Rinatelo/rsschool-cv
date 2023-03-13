# Rinat Abzalutdinov
      ### Junior Frontend Developer

      ---

      ### Contact information:
      **Address:**Moscow
      **Phone:** +7 909 0999660
      **E-mail:** rinat.abzalutdinov@gmail.com
      **Telegram:** [rinatAbzalutdinov](https://t.me/rinatAbzalutdinov)
      **LinkedIn** [Rinat Abzalutdinov](https://www.linkedin.com/in/rinat-abzalutdinov-82a883239/)
      **GitHub**[Rinatelo](https://github.com/Rinatelo)

      ---

      ### The Person Behind the Profile:
      My name is Rinat and I am a junior frontend developer with a passion for building beautiful and functional websites. From a young age, I have always been interested in technology and how it can be used to create new and exciting experiences online.

      I pursued my passion by studying computer science at university and honing my skills through various online courses and personal projects. Through these experiences, I have developed proficiency in HTML, CSS, JavaScript, and several popular frontend frameworks.

      In addition to technical skills, I have a strong eye for design and enjoy creating visually appealing websites that are easy to use and navigate. I am also a strong communicator and enjoy working collaboratively with team members to achieve project goals.

      Aside from my interest in programming, I also love to travel, snowboard, and go hiking. Exploring new places and challenging myself in physical activities are some of my favorite pastimes.

      As a lifelong learner, I am always seeking new challenges and opportunities to grow as a developer. I am excited to contribute my skills and passion to a dynamic team and help create innovative and engaging websites that make a positive impact on users.
      ---

      ### Skills and Proficiency:
      * HTML5, CSS3
      * JavaScript Basics
      * ReactJS Basics
      * Git, GitHub, GitLab
      * BEM
      * VS Code, IntelliJ IDEA
      * Figma, Adobe Photoshop

      ---

      ### Code example:
      **Implementing Bubble Sort in Javascript from HTMLacademy:**
      _During the training, I make several jumps and collect the lengths of the jumps into an array called "attempts".
      The qualification value is stored in the variable "qualificationDistance".
      The program should select the three best jumps, calculate the average value of these three jumps, and store it in a variable called "averageBest".
      If the average of the best three jumps is greater than the qualification value, then I have passed the qualification and the variable "qualified" should contain "true". If the qualification is not passed, then "qualified" should contain "false"._

      ```javascript
      let qualificationDistance = 200;
      let attempts = [120, 150, 160, 201, 203, 180, 202];
      let qualified = false;

       for (let i = 0; i < attempts.length - 1; i++) {
         for (let j = 0; j < attempts.length - 1 - i; j++) {
           if (attempts[j] < attempts[j + 1]) {
             const temp = attempts[j];
             attempts[j] = attempts[j + 1];
             attempts[j + 1] = temp;
           }
         }
       }

      // Выбор лучших трёх прыжков
      const bestThree = attempts.slice(0, 3);

      // Вычисление среднего значения
      const averageBest = bestThree.reduce((sum, jump) => sum + jump, 0) / bestThree.length;

      // Проверка прохождения квалификации
      if (averageBest > qualificationDistance) {
        qualified = true;
      }
      ```

      ---

      ###Education
      *University: 
       *Nosov Magnitogorsk State Technical University
       *Innopolis University
      *Courses: 
       *HTML academy
       *Skillbox
       *Stepik

      ---

      ###Experience
      *I used to work as an equipment maintenance and repair engineer
      *Little experience in JS and frontend development. Worked in a team on several small projects and currently working.
      *Currently, I am gaining practical experience working with JavaScript by working on a web application project at RS School. I have studied various JavaScript libraries and frameworks such as React and Node.js and applied them to create dynamic and interactive user interfaces.

      ---

      ###Languages
      *Russian: native
      *English: A2 (B1 in process…)
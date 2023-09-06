# Task-1-4-Responsive-landing-page-using-HTML-CSS-JS--main---Copy
*/start from here*/
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Responsive Landing Page using HTML, CSS & Javascript</title>
    <link rel="stylesheet" href="style.css" />
    <link
      href="https://cdn.jsdelivr.net/npm/remixicon@2.5.0/fonts/remixicon.css"
      rel="stylesheet"
    />
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet" />
  </head>
  <body>
    <header class="container header">
      <nav class="nav">
        <div class="logo">
          <h2>JEELANI Portfolio</h2>
        </div>
        <div class="nav_menu" id="nav_menu">
          <button class="close_btn" id="close_btn">
            <i class="ri-close-fill"></i>
          </button>
          <ul class="nav_menu_list">
            <li class="nav_menu_item">
              <a href="#" class="nav_menu_link">skills</a>
            </li>
            <li class="nav_menu_item">
              <a href="#" class="nav_menu_link">about</a>
            </li>
            <li class="nav_menu_item">
              <a href="#" class="nav_menu_link">experience</a>
            </li>
            <li class="nav_menu_item">
              <a href="#" class="nav_menu_link">contact</a>
            </li>
          </ul>
        </div>
        <button class="toggle_btn" id="toggle_btn">
          <i class="ri-menu-line"></i>
        </button>
      </nav>
    </header>
    <section class="wrapper">
      <div class="container">
        <div class="grid-cols-2">
          <div class="grid-item-1">
            <h1 class="main-heading">
              Welcome to <span>JEELANI Portfolio Page</span>
              <br />
               
            </h1>
            <p class="info-text">
              Prodigy infotech Task 1&4 "create a responsive landing page & personal Portfolio"
            </p>
            <div class="btn_wrapper">
              <button class="btn view_more_btn">
                Responsive landing Page <i class="ri-arrow-right-line"></i>
              </button>
              <button class="btn documentation_btn">personal Portfolio</button>
            </div>
          </div>
          <div class="grid-item-2">
            <div class="team_img_wrapper">
              <img src="./1.jpg" alt="team-img" />
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="wrapper">
      <div class="container" data-aos="fade-up" data-aos-duration="1000">
        <div class="grid-cols-3">
          <div class="grid-col-item">
            <div class="icon">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M9.75 17L9 20l-1 1h8l-1-1-.75-3M3 13h18M5 17h14a2 2 0 002-2V5a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"
                />
              </svg>
            </div>
            <div class="featured_info">
              <span>skills </span>
              <p>
                <pre>1- C Language</pre>
                <pre>2- C++ Language</pre>
                <pre>3- Python Language</pre>
                <pre>4- Data Structure and Algorithm</pre>
                <pre>5- Machine Learning</pre>
                <pre>6- Data Science</pre>
              </p>
            </div>
          </div>
          <div class="grid-col-item">
            <div class="icon">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M17 14v6m-3-3h6M6 10h2a2 2 0 002-2V6a2 2 0 00-2-2H6a2 2 0 00-2 2v2a2 2 0 002 2zm10 0h2a2 2 0 002-2V6a2 2 0 00-2-2h-2a2 2 0 00-2 2v2a2 2 0 002 2zM6 20h2a2 2 0 002-2v-2a2 2 0 00-2-2H6a2 2 0 00-2 2v2a2 2 0 002 2z"
                />
              </svg>
            </div>
            <div class="featured_info">
              <span>Experience</span>
              <p>
                <pre>1- Data Analyst virtual internship
                    offered By edunet Foundation
                    from 12th june to 24th july 2023</pre>
              </p>
              <p>
                  <pre>2- web development virtual internship
                  offered by Prodigy infotech 
                  from 1 August to 31 August 2023
                </pre>
              </p>
            </div>
          </div>
          <div class="grid-col-item">
            <div class="icon">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M10 20l4-16m4 4l4 4-4 4M6 16l-4-4 4-4"
                />
              </svg>
            </div>
            <div class="featured_info">
              <span>Qualification</span>
              <p>
                <pre>*BCA From CSJMU kanpur 2021</pre>
                <pre>*Pursuing MCA(AI/ML) From LNCTU Bhopal 2024</pre>
              </p>
            </div>
          </div>
        </div>
      </div>
    </section>
    <footer></footer>
    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.8.0/gsap.min.js"></script>
    <script src="script.js" defer></script>
  </body>
</html>

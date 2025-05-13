<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1" />
<title>Professional Bio - Manish</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Merriweather:wght@400;700&family=Montserrat:wght@400;600&display=swap');

  /* Reset and base */
  * {
    box-sizing: border-box;
  }
  body {
    margin: 0;
    min-height: 100vh;
    background: linear-gradient(135deg, #1f2937 0%, #111827 100%);
    font-family: 'Montserrat', sans-serif;
    color: #eae6df;
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 1.5rem;
    overflow: hidden;
  }
  .bio-container {
    background-color: rgba(30, 41, 59, 0.9);
    max-width: 440px;
    width: 100%;
    padding: 2.5rem 2rem 3rem 2rem;
    border-radius: 16px;
    box-shadow: 0 16px 32px rgba(0, 0, 0, 0.8);
    text-align: center;
    position: relative;
    overflow: hidden;
  }

  .profile-pic {
    width: 140px;
    height: 140px;
    border-radius: 50%;
    border: 4px solid #c9b375;
    box-shadow: 0 0 10px #c9b375aa;
    object-fit: cover;
    margin-bottom: 1.5rem;
    transition: transform 0.3s ease;
  }
  .profile-pic:hover,
  .profile-pic:focus {
    outline: none;
    transform: scale(1.05);
    box-shadow: 0 0 20px #c9b375dd;
  }

  h1 {
    font-family: 'Merriweather', serif;
    font-size: 2.4rem;
    font-weight: 700;
    margin: 0 0 0.25rem 0;
    color: #f3e8c9;
    text-shadow: 0 2px 6px #00000080;
  }
  h2 {
    font-weight: 600;
    font-size: 1.25rem;
    color: #c9b375;
    margin: 0 0 1.5rem 0;
    letter-spacing: 0.06em;
  }
  p {
    font-size: 1rem;
    line-height: 1.6;
    color: #d8d4c8;
    margin-bottom: 1.4rem;
  }

  /* Social links container */
  .social-links {
    display: flex;
    justify-content: center;
    gap: 2rem;
    margin-top: 1rem;
  }

  /* Social link styles */
  .social-links a {
    color: #c9b375;
    font-weight: 600;
    text-decoration: none;
    font-size: 1rem;
    position: relative;
    transition: color 0.3s ease;
    padding-bottom: 2px;
    display: flex;
    align-items: center;
    gap: 0.4rem;
  }
  .social-links a svg {
    flex-shrink: 0;
  }
  .social-links a::after {
    content: '';
    position: absolute;
    left: 0;
    bottom: 0;
    width: 0%;
    height: 2px;
    background: #c9b375;
    transition: width 0.3s ease;
  }
  .social-links a:hover,
  .social-links a:focus {
    color: #f3e8c9;
  }
  .social-links a:hover::after,
  .social-links a:focus::after {
    width: 100%;
  }

  /* Accessibility focus outlines */
  a:focus,
  button:focus,
  .profile-pic:focus,
  .address:focus {
    outline: 3px solid #c9b375;
    outline-offset: 2px;
  }

  /* Responsive */
  @media (max-width: 480px) {
    .bio-container {
      padding: 2rem 1.4rem 2.6rem 1.4rem;
    }
    h1 {
      font-size: 2rem;
    }
    h2 {
      font-size: 1.1rem;
    }
    p {
      font-size: 0.9rem;
      margin-bottom: 1.2rem;
    }
    .social-links {
      gap: 1.2rem;
    }
    .social-links a {
      font-size: 0.9rem;
    }
    .profile-pic {
      width: 120px;
      height: 120px;
      margin-bottom: 1.2rem;
      border-width: 3px;
      box-shadow: 0 0 8px #c9b375bb;
    }
 
</style>
</head>
<body>
  <main class="bio-container" role="region" aria-label="User biography">
    <img src="unf.jpg"  class="profile-pic" tabindex="0" />
    <h1>Manish</h1>
    <h2> Social Media Expert</h2>
    <p>Greetings! I am <strong>Manish</strong>, a dedicated professional specializing in social media management. I focus on delivering high-quality, innovative online experiences for businesses and individuals.</p>
    <p>When I'm not coding or strategizing, I enjoy connecting people and exploring new digital trends. Feel free to reach out through any of the platforms below.</p>
    <nav class="social-links" aria-label="Social media links">
      <a href="https://instagram.com/manishhhhh.28" target="_blank" rel="noopener" aria-label="Instagram Profile">
        <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" fill="#c9b375" viewBox="0 0 24 24" >
          <path d="M7 2C4.243 2 2 4.243 2 7v10c0 2.757 2.243 5 5 5h10c2.757 0 5-2.243 5-5V7c0-2.757-2.243-5-5-5H7zm10 2c1.65 0 3 1.35 3 3v10c0 1.65-1.35 3-3 3H7c-1.65 0-3-1.35-3-3V7c0-1.65 1.35-3 3-3h10zm-5 3a5 5 0 1 0 0 10a5 5 0 0 0 0-10zm0 2a3 3 0 1 1 0 6a3 3 0 0 1 0-6zm4.75-.25a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 0 1 0-2.5z"/>
        </svg>
        instagram
      </a>
      <a href="mailto:manishrawool28@gmail.com" target="_blank" rel="noopener" aria-label="Send Email to Manish">
        <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" fill="#c9b375" viewBox="0 0 24 24">
          <path d="M2 5a2 2 0 0 1 2-2h16a2 2 0 0 1 2 2v14a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2V5zm2 0v.511l8 5.3 8-5.3V5H4zm0 2v11h16V7.511l-8 5.3-8-5.3z"/>
        </svg>
        Email
      </a>
      <a href="https://wa.me/8237280930" target="_blank" rel="noopener" aria-label="WhatsApp Chat with Manish">
        <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" fill="#c9b375" viewBox="0 0 24 24">
          <path d="M20.52 3.48A11.93 11.93 0 0 0 3.48 20.52L2 22l1.56-3.68A11.93 11.93 0 0 0 20.52 3.48zm-2.4 15.97c-1.6.85-3.28 1.54-5.07 1.87a7.64 7.64 0 0 1-3.88-.44c-.07-.03-.18-.04-.3-.05-.29-.02-.67-.05-1.04-.36-.35-.29-.87-.85-1.31-1.72-.42-.82-.133-1.5.22-1.83.14-.15.33-.41 3.92-3.42 1.09-1 2.02-1.3 2.42-1.46a1.96 1.96 0 0 1 1.6 0c.26.12 1.03.48 1.25.58.2.1.34.15.49.22.16.09.3.21.44.38.14.15.07.27.07.55 0 .29-.22.57-.31.68-.1.11-.2.24-.3.36-.1.12-.21.29-.3.39-.07.07-.13.16-.19.24-.02.04-.06.1-.06.13s.01.08.03.11c.05.06.12.02.26-.01.14-.03 1.05-.41 1.21-.48.16-.07.27-.1.38-.07.12.03.77.37.87.44.11.06.19.13.28.26.09.14.03.43-.15.68-.19.25-.46.46-.66.61z"/>
        </svg>
        WhatsApp
      </a>
    </nav>
  </main>
</body>
</html>

* {
  box-sizing: border-box;
}

body {
    color: #2e2f42;
    background-color: #ffffff;
    font-family: "Roboto", sans-serif;
    font-size: 16px;
    font-style: normal;
    line-height: 1.5;
    letter-spacing: 2;
  }
  
  h1,
  h2,
  h3,
  h4,
  h5,
  h6,
  p {
    margin: 0;
  }
  
  ul {
    margin: 0;
    padding-left: 0;
    list-style: none;
  }
  
  a {
    text-decoration: none;
  }
  
  .header {
    border-bottom: 1px solid #e7e9fc;
  box-shadow: 0 1px 6px 0 rgba(46, 47, 66, 0.08),
    0 1px 1px 0 rgba(46, 47, 66, 0.16), 0 2px 1px 0 rgba(46, 47, 66, 0.08);
}
  }
  
  .header-container {
    display: flex;
    align-items: center;
    padding: 0 15px;
  }
  
  .container {
    width: 1158px;
    margin: 0 auto;
    padding: 0 15px;
  }
  
  .navigation {
    display: flex;
    align-items: center;
    margin-right: auto;
  }
  
  .header-logo {
    margin-right: 76px;
    padding: 24px 0;
    font-family: "Raleway", sans-serif;
    font-size: 18px;
    font-weight: 700;
    line-height: 1.17;
    letter-spacing: 0.03em;
    text-transform: uppercase;
    color: #4d5ae5;
  }
  
  .nav-list {
    display: flex;
    gap: 40px;
    align-items: center;
    margin-right: auto;
  }
  
  .nav-link {
    display: block;
    padding: 24px 0;
    font-weight: 500;
    line-height: 1.5;
  letter-spacing: 0.02em;
  color: #2e2f42;
  }
  
  .address-list {
    display: flex;
    align-items: center;
    gap: 40px;
    font-weight: 400;
    font-size: 16px;
    font-style: normal;
    line-height: 1.5;
    letter-spacing: 0.02em;
    color: #434455;
  }
  
  
  .footer {
    padding: 100px 0;
    background-color: #2e2f42;
  }
  
  .footer-link {
    display: inline-block;
    margin-bottom: 16px;
    font-family: "Raleway", sans-serif;
    font-size: 18px;
    font-weight: 700;
    line-height: 1.17;
    letter-spacing: 0.03em;
    text-transform: uppercase;
    color: #4d5ae5;
  }
  
  .logo-light {
    color: #f4f4fd;
  }
  
  .footer-text {
    max-width: 264px;
    color: #f4f4fd;
    line-height: 1.5;
    letter-spacing: 0.02em;
  }

  .social-link-footer{
    gap: 16px;
    justify-content: center;
    margin-top: 10px;
    display: flex;
    align-items: center;
    width: 40px;
    height: 40px;
    border-radius: 50%;
    background-color: #4d5ae5;
    text-decoration: none;
  }

  .social-link-footer:hover {
    background-color: #404bbf;
}

  .subtitle-footer{
    display: flex;
    justify-content: center;
    font-weight: 500;
font-size: 16px;
line-height: 1.5;
letter-spacing: 0.02em;
color: #fff;
margin: 0;
padding-bottom: 8px;
  }
  
  .social-links {
    display: flex;
    gap: 16px;
    list-style: none;
    padding: 0;
  }

  .footer-socials {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    margin-top: -20px;
    justify-content: center;
}

  .logo {
    display: inline-block;
    font-family: "Raleway", sans-serif;
    font-size: 18px;
    font-weight: 700;
    line-height: 1.17;
    letter-spacing: 0.03em;
    text-transform: uppercase;
    color: #4d5ae5;
    margin-bottom: 16px;
  }
  
  .span-logo {
    color: #2e2f42;
  }
  
  .nav-link:hover,
  .nav-link:focus {
    color: #2e2f42;
  }
  
  .contacts {
    font-style: normal;
    margin-left: auto;
  }
  
  .contacts-list {
    display: flex;
    gap: 40px;
  }
  
  .hero {
    padding: 188px 0;
    background-color: #2e2f42;
    background-image: url("//images/people-office\ 1\ \(1\).jpg;");
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    color: #ffffff;
  
  }
  
  .hero .container {
    flex-direction: column;
    align-items: center;
    gap: 48px;
  }
  
  .hero-title {
    max-width: 496px;
    margin-bottom: 48px;
    margin-left: auto;
    margin-right: auto;
    color: #ffffff;
    text-align: center;
    font-size: 56px;
    font-weight: 700;
    line-height: 1.07;
    letter-spacing: 0.02em;
  }
  
  .hero-button {
    display: block;
    min-width: 169px;
    height: 56px;
    margin: 0 auto;
    border: none;
    border-radius: 4px;
    background-color: #4d5ae5;
    cursor: pointer;
    color: #ffffff;
    font-weight: 500;
    line-height: 1.5;
    letter-spacing: 0.04em;
  }
  
  .hero-button:hover,
  .hero-button:focus {
    background-color: #404bbf;
  }
  
  .team {
    padding: 120px 0;
    background-color: #f4f4fd;
  }
  
  .section-title {
    margin-bottom: 72px;
    color: #2e2f42;
    text-align: center;
    font-size: 36px;
    font-weight: 700;
    line-height: 1.11;
    letter-spacing: 0.02em;
    text-transform: capitalize;
  }
  
  .section-title-team {
    margin-bottom: 72px;
    font-weight: 700;
  font-size: 36px;
  line-height: 1.11;
  letter-spacing: 0.02em;
  text-align: center;
  color: #2e2f42;
  }
  
  .team-list {
    display: flex;
    gap: 24px;
  }
  
  .team-item {
    width: calc((100% - 72px) / 4);
    border-radius: 0px 0px 4px 4px;
    background-color: #ffffff;
  }
  
  .team-card-content {
    padding: 32px 0;
  }
  
  .subtitle {
    margin-bottom: 8px;
    color: #2e2f42;
    font-size: 20px;
    font-weight: 500;
    line-height: 1.2;
    letter-spacing: 0.02em;
  }
  
  .subtitle-team {
    margin-bottom: 8px;
    font-weight: 500;
    font-size: 20px;
    line-height: 1.2;
    letter-spacing: 0.02em;
    text-align: center;
    color: #2e2f42;
  }
  
  .text {
    color: #434455;
    line-height: 1.5;
    letter-spacing: 0.02em;
  }
  
  .text-team {
    font-weight: 400;
    font-size: 16px;
    line-height: 1.5;
    letter-spacing: 0.02em;
    text-align: center;
    color: #434455; 
  }
  
  img {
    display: block;
    max-width: 100%;
    height: auto;
  }

.social-icon-footer {
  width: 24px;
  height: 24px;
}

  .social-link {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    width: 40px;
    height: 40px;
    border-radius: 50%;
    background-color: #4d5ae5;
    text-decoration: none;
}

.social-link img {
    width: 16px;
    height: 16px;
}

.social-link:hover {
    background-color: #404bbf;
}

.team-social-links {
    display: flex;
    gap: 10px;
    justify-content: center;
    margin-top: 10px;
}
  
  .about {
    padding: 120px 0;
  }
  
  .about-list {
    display: flex;
    gap: 24px;
  }
  
  .about-item {
    flex-basis: calc((100% - 72px) / 4);
  }
  
  .visually-hidden {
    position: absolute;
    width: 1px;
    height: 1px;
    margin: -1px;
    border: 0;
    padding: 0;
    white-space: nowrap;
    clip-path: inset(100%);
    clip: rect(0 0 0 0);
    overflow: hidden;
  }
  
  .portfolio {
    padding: 120px 0;
  }
  
  .portfolio-list {
    display: flex;
    flex-wrap: wrap;
    column-gap: 24px;
    row-gap: 48px;
  }
  
  .portfolio-item {
    width: calc((100% - 48px) / 3);
  }
  
  .portfolio-card-content {
    padding: 32px 16px;
    border: 1px solid #e7e9fc;
    border-top: none;
  }
  
  .section {
    padding: 120px 0;
  }
  
  .features {
    padding: 120px 0;
  }
  
  .features-list {
    display: flex;
    gap: 24px;
  }
  
  .features-item {
    flex-basis: calc((100% - 72px) / 4);
  }
  
  .features-subtitle {
    margin-bottom: 8px;
    color: #2e2f42;
    font-size: 20px;
    font-weight: 500;
    line-height: 1.2;
    letter-spacing: 0.02em;
  }
  
  .features-text {
    color: #434455;
    line-height: 1.5;
    letter-spacing: 0.02em;
  }
  
  .advantages {
    padding: 120px 0;
  }
  
  .advantages-list {
    display: flex;
    gap: 24px;
  }
  
  .advantages-item {
    flex-basis: calc((100% - 72px) / 4);
  }
  
  .advantages-subtitle {
    margin-bottom: 8px;
    color: #2e2f42;
    font-size: 20px;
    font-weight: 500;
    line-height: 1.2;
    letter-spacing: 0.02em;
  }
  
  .advantages-text {
    color: #434455;
    line-height: 1.5;
    letter-spacing: 0.02em;
  }
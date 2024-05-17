<template>
  <section id="resume" class="resume">
    <div class="container">

      <div class="section-title">
        <h2>Resume</h2>
        <p>Check My Resume</p>
        <a href="https://drive.google.com/file/d/1baA0IEWAcJy48Ox1Jer-tlrU8oyCnqfh/view?usp=sharing" download="siyamthandaTsoboCV.pdf" class="btn btn-primary" target="blank">Download Resume</a>
        
      </div>

      <div class="row">
        <div class="col-lg-6">
          <h3 class="resume-title">Summary</h3>
          <div class="resume-item pb-0">
            <h4>Siyamthanda Tsobo</h4>
            <p><em>Goal-oriented technical intern specializing in various modernly used technologies</em></p>
            <ul>
              <li>ikhwezi park, Khayelitsha, Cape Town</li>
              <li>(+27) 67226-5196</li>
              <li>siyamthandatsobo@gmail.com</li>
            </ul>
          </div>

          <h3 class="resume-title">Education</h3>
          <div class="resume-item">
            <h4>Full-stack development</h4>
            <h5>2023-2024</h5>
            <p><em>Life Choices Academy, Cape Town, SOUTH AFRICA</em></p>
            <p>I have undergone 6 months of training as a full-stack developer which has improved my analytical skills, and also soft skills training</p>
          </div>
          <div class="resume-item">
            <h4>HIGH SCHOOL Matric Certificate</h4>
            <h5>2022</h5>
            <p><em>SPES BONA HIGH, ATHLONE, SOUTH AFRICA</em></p>
            <p>I completed my matric studies and showed proficiency in the STEM field</p>
          </div>
          <div class="resume-item">
            <h4>Applications development</h4>
            <h5>2021</h5>
            <p><em>MTN BUSINESS APP ACADEMY/ IT VARSITY, SOUTH AFRICA</em></p>
            <p>Underwent training in Android app development for 6 weeks using KOTLIN development language</p>
          </div>
        </div>

        <div class="col-lg-6">
          <h3 class="resume-title">Professional Experience</h3>
          <div class="resume-item">
            <h4>Life Choices Studio Intern</h4>
            <h5>2024 - Present</h5>
            <p><em>CLAREMONT, CAPE TOWN, RSA </em></p>
            <ul>
              <li>Proficiency in JavaScript, Node, Vue.js, Bootstrap, MYSQL</li>
              <li>Understanding of software development lifecycle and best practices.</li>
              <li>Demonstrated strong problem-solving skills and adaptability in learning new technologies and methodologies.</li>
              <li>Received positive feedback from team members for proactive attitude and willingness to take on new challenges</li>
              <li>Participated in Scrum practices, including sprint planning, daily stand-ups, and
retrospectives, contributing to efficient and collaborative project delivery.</li>
<li>Currently learning networking with Cisco and AWS to expand my technical skill set
and enhance my understanding of network infrastructure and cloud services</li>
            </ul>
          </div>
          <div class="resume-item">
            <h4>Volunteer BACKEND DEVELOPER & SQUAD LEADER</h4>
            <h5>2024-Present</h5>
            <p><em>APLENTIFY, LAGOS, NIGERIA</em></p>
            <ul>
              <li>Collaborating with a team of 10+ developers to build Aplentify, a new product from scratch, ensuring efficient backend architecture and robust API design.</li>
              <li>Collaborating in agile development processes, including sprint planning, stand-ups, and retrospectives, to deliver features on schedule.</li>
              <li>Designated as squad leader based on the recommendation of the Product Owner, citing my strong interpersonal abilities and effective communication skills</li>
            </ul>
          </div>
          <div class="resume-item">
            <h4>CALL CENTRE AGENT</h4>
            <h5>2023</h5>
            <p><em>CALL CENTRE INTERNATIONAL WYNBERG, CPT</em></p>
            <ul>
              <li>Answered inbound calls promptly and professionally, addressing customer inquiries, concerns, and requests.</li>
              <li>Provided expert assistance and support to customers, troubleshooting technical issues and guiding them through solutions.</li>
              <li>Resolved customer complaints effectively, ensuring high levels of satisfaction and retention</li>
              <li>Collaborated with team members and other departments to streamline processes and improve customer service delivery.</li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  methods: {
    downloadResume() {
      // Replace this with the actual link to your resume file
      const resumeLink = 'https://drive.google.com/file/d/1ezDDE9BK2ux2kEECnSJMqtzI68IOAQT1/view?usp=sharing';

      // Create a temporary anchor element to trigger the download
      const downloadLink = document.createElement('a');
      downloadLink.href = resumeLink;
      downloadLink.download = 'Siyamthanda_Tsobo_Resume.pdf';
      document.body.appendChild(downloadLink);
      downloadLink.click();
      document.body.removeChild(downloadLink);
    }
  }
}
</script>
<style scoped>
.btn {
  display: inline-block;
  background-color: white;
  color:black;
  padding: 5px 10px;
  text-decoration: none;
  border-radius: 5px;
  transition: background-color 0.3s ease;
}

.btn:hover {
  background-color: #18d26e;
}
.container {
  animation: slide-up 0.5s ease-in-out forwards;
  opacity: 0;
  transform: translateY(50px);
}
@keyframes slide-up {
  from {
    opacity: 0;
    transform: translateY(50px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}
</style>
---
###################### hero slider ###########################
slider:
  enable: true
  slider_item:
    # slider item loop
    - bg_image: images/banner/powertrain.jpg
      animation_from: left
      subtitle: We are here to
      title: Design your EV Powertrain
      content: We specialize in crafting cutting-edge electric powertrains and expertise to <br> propel your vehicles into a sustainable and efficient future.
      pagination_icon: ti-bolt
      pagination_name: Powertrain Design
      textWhite: true
      button:
        enable: true
        label: More details
        link: "about/"

    # slider item loop
    - bg_image: images/banner/banner-2.jpg
      animation_from: up
      subtitle: We help you to
      title: Get your Projects running
      content: Empowering your vision, we provide comprehensive support to your projects <br> and ensuring successful realization of your goals.
      pagination_icon: ti-comments # themify icon pack : https://themify.me/themify-icons
      pagination_name: Consulting
      button:
        enable: true
        label: More details
        link: "about/"

    # slider item loop
    - bg_image: images/banner/systemy.jpg
      animation_from: down
      subtitle: We enable you to
      title: Use AI to design your EV
      content: Unlock the potential of artificial intelligence in electric vehicle design <br> with our expertis for efficient development.
      pagination_icon: ti-pulse # themify icon pack : https://themify.me/themify-icons
      pagination_name: SYSTEMY
      textWhite: true
      button:
        enable: true
        label: More details
        link: "about/"

################################ clients logo slider ################################
clients_logo_slider:
  enable: true
  client_logos:
    - logo: "images/client-logo/schaeffler.png"
      link: "https://schaeffler.de/"
    - logo: "images/client-logo/kreisel.svg"
      link: "https://www.kreiselelectric.com/"
    - logo: "images/client-logo/aox.png"
      link: "https://www.aox.de/"
    - logo: "images/client-logo/movia.png"
      link: "https://www.movia-technologies.com/"
    - logo: "images/client-logo/eberspaecher.png"
      link: "https://www.eberspaecher.com/"
    - logo: "images/client-logo/voyah.png"
      link: "https://www.voyah.ch/"
    - logo: "images/client-logo/hoerbiger.png"
      link: "https://www.hoerbiger.com/"
    - logo: "images/client-logo/nidec.png"
      link: "https://www.nidec.com/en/"
    - logo: "images/client-logo/mahle.png"
      link: "https://www.mahle.com/"

########################################## Service ####################################
service:
  enable: true
  title: "Service We Provide"
  subtitle: "Best Service"
  section: "service" # showing items from service section
  # service item comes from "content/service" folder

######################################## About #########################################
about:
  enable: true
  bg_image: "images/background/about-bg.jpg"
  title: "Who We Are?"
  content: "Driving the Future of Energy Storage: Unraveling Our Commitment and Expertise in Advanced Battery Management Systems."
  # bullet point
  bullet_point:
    - "Business Services"
    - "EV Motor Design"
    - "AI powered Design"
    - "Battery Management Systems"
    - "Electric Powertrain"
    - "Audit & Assurance"
  button:
    enable: true
    label: "Explore More"
    link: "about/"

##################################### Skill ##############################################
skill:
  enable: false
  subtitle: Our Skills
  title: Why Choose Us
  content: Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed eiusmod tempor incididunt laboris nisi ut aliquip ex ea commodo consequat. <br><br> Duis aute irure dolor in reprehenderit voluptate velit esse cillum dolore fugiat nulla pariatur. Excepteur sint ocaecat cupidatat non proident sunt culpa qui officia deserunt mollit anim id est laborum. sed perspiciatis unde omnisiste natus error sit voluptatem accusantium.doloremque ladantium totam rem aperieaque ipsa quae ab illo inventore.veritatis. et quasi architecto beatae vitae dicta sunt explicabo.
  # funfacts
  funfacts:
    - icon: ti-server # themify icon pack : https://themify.me/themify-icons
      title: Projects Done
      count: 230

    - icon: ti-face-smile # themify icon pack : https://themify.me/themify-icons
      title: Satisfied Clients
      count: 789

    - icon: ti-thumb-up # themify icon pack : https://themify.me/themify-icons
      title: Cup Of Coffee
      count: 580

  # progressbar
  progressbar:
    - title: Branding
      progress: 85%

    - title: Consulting
      progress: 90%

    - title: Business
      progress: 75%

    - title: Promotion
      progress: 90%

########################################## project ####################################
project:
  enable: true
  title: "Latest Projects"
  subtitle: "Our Works"
  section: "project" # showing items from project section
  # project item comes from "content/project" folder

########################################### Mission ###################################
mission:
  enable: false
  subtitle: Our Goal
  title: Company Mission
  content: Lorem ipsum dolor sit amet consectetur adipisicing elit sed eiusmod tempor didunt laboris nisi ut aliquip ex ea commodo consequat.
  image: images/chart.png
  accordion:
    - title: Our Company Mission
      description: Duis aute irure dolor in reprehenderit voluptate velit esse cillum dolore fugiat nulla pariatur.Excepteur sint ocaecat cupidatat non proident sunt culpa qui officia deserunt mollit anim id est laborum.

    - title: Our Company Vision
      description: Duis aute irure dolor in reprehenderit voluptate velit esse cillum dolore fugiat nulla pariatur.Excepteur sint ocaecat cupidatat non proident sunt culpa qui officia deserunt mollit anim id est laborum.

    - title: Our Company Goal
      description: Duis aute irure dolor in reprehenderit voluptate velit esse cillum dolore fugiat nulla pariatur.Excepteur sint ocaecat cupidatat non proident sunt culpa qui officia deserunt mollit anim id est laborum.

##################################### Promo video ####################################
promo_video:
  enable: false
  title: "We Are Alawys <br> Comitted"
  bg_image: "images/background/promo-video.jpg"
  video_URL: "https://www.youtube.com/embed/ResipmZmpDU"
  video_title: "Lorem ipsum dolor <br> sit amet con."

##################################### call to action #################################
testimonial:
  enable: false
  subtitle: Clients
  title: What client Say
  image: images/client.png
  testimonial_item:
    - name: Julia Robertson
      content: Lorem ipsum dolor sit amet constur adipisicing elit sed eiusmtempor incid sed dolore magna aliqu enim minim veniam quis nostrud exercittion ullamco labo ris nisi aliquip excepteur.
      designation: Happy Clients

    - name: Julia Robertson
      content: Lorem ipsum dolor sit amet constur adipisicing elit sed eiusmtempor incid sed dolore magna aliqu enim minim veniam quis nostrud exercittion ullamco labo ris nisi aliquip excepteur.
      designation: Happy Clients

    - name: Julia Robertson
      content: Lorem ipsum dolor sit amet constur adipisicing elit sed eiusmtempor incid sed dolore magna aliqu enim minim veniam quis nostrud exercittion ullamco labo ris nisi aliquip excepteur.
      designation: Happy Clients

##################################### call to action #################################
call_to_action:
  enable: true
  bg_image: "images/background/cta.jpg"
  title: "Ready to transform your energy storage capabilities? Contact us today."
  button:
    enable: true
    label: "Contact"
    link: "contact/"

########################################## blog ####################################
blog:
  enable: true
  title: "Company News"
  subtitle: "Latest News"
  section: "blog"
  # blog item comes from "content/blog" folder
---

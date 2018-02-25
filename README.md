# Curriculum-Vitae
Es el código sobre información personal.
`extends layout

block content

   body
    // banner
    #home.banner
      .banner-agileinfo
        // header
        .header
          .container
            .logo
              h1
                a(href='index.html') Curriculum Vitae
            .menu
              a#menuToggle(href='')
                span.navClosed
              nav
                a.active(href='index.html') Inicio
                a.scroll(href='#about') Acerca de mí
                a.scroll(href='#skills') Mis Habilidades
                a.scroll(href='#services') Otros
                a.scroll(href='#experience') Mi Educación
                a.scroll(href='#education') Experiencia
                a.scroll(href='#projects') Aptitudes
            .clearfix  
        // //header
        .banner-main
          .container
            .col-md-5.banner-left
              img(src='/images/IMG_8200.jpg', alt='')
            .col-md-7.banner-text
              p Que tal
              h2
                span Soy Hugo Yadiel Ficachi Hernández
                |  ISC
              .w3agile_hire_right
                a.wthree-more.w3more1.nina.scroll(href='#about', data-text='Conoceme')
                  span c
                  span o
                  span n
                  span o
                  span c
                  span e
                  span m
                  span e
                  
    // //banner
    // about
    #about.about
      .container
        h3.w3l-title Contacto
        .about-w3l-agileifo-grid
          .col-md-6.agile-w3l-ab
            ul#slider.rslides
              li
                .agile-w3l-ab-img
                  img.img-responsive(src='images/IMG_8200.jpg', alt='Homey Designs')
              li
                .agile-w3l-ab-img
                  img.img-responsive(src='images/IMG_8200.jpg', alt='Homey Designs')
              li
                .agile-w3l-ab-img
                  img.img-responsive(src='images/IMG_8200.jpg', alt='Homey Designs')
          .col-md-6.w3ls-agile-left
            .w3ls-agile-left-info
              h4 Nombre
              p Hugo Yadiel Ficachi Hernández
            .w3ls-agile-left-info
              h4 Fecha de Nacimiento
              p 19 de Mayo de 1996
            .w3ls-agile-left-info
              h4 Dirección
              p  Calle 5 de mayo #26, Soconusco Veracruz
            .w3ls-agile-left-info
              h4 Celular
              p 9241428992
            .w3ls-agile-left-info
              h4 Facebook
              p
                a(href='https://www.facebook.com/yadielficachi') Yadiel Ficachi
            .w3ls-agile-left-info
              h4 Correo
              p
                a(href='yadielficachi@gmail.com') yadielficachi19@gmail.com
    // //about
    // stats
    #skills.stats.wthree-sub
      .container
        h3.w3l-title Mis Habilidades
        .col-sm-6.stats_grid_right
          .skillbar(data-percent='20')
            span.skillbar-title(style='background: #f1703a;') Java
            p.skillbar-bar(style='background: #f88c5e;')
            span.skill-bar-percent
          // End Skill Bar
          .skillbar(data-percent='20')
            span.skillbar-title(style='background: #2980b9;') JavaScript
            p.skillbar-bar(style='background: #3498db;')
            span.skill-bar-percent
          // End Skill Bar
          .skillbar(data-percent='20')
            span.skillbar-title(style='background: #a0d034;') HTML
            p.skillbar-bar(style='background: #b2ec2f;')
            span.skill-bar-percent
          // End Skill Bar
        .col-sm-6.stats_grid_right
          .skillbar(data-percent='20')
            span.skillbar-title(style='background: #f1703a;') BOOTSTRAP
            p.skillbar-bar(style='background: #f88c5e;')
            span.skill-bar-percent
          // End Skill Bar
          .skillbar(data-percent='30')
            span.skillbar-title(style='background: #2980b9;') CSS3
            p.skillbar-bar(style='background: #3498db;')
            span.skill-bar-percent
          // End Skill Bar
          .skillbar(data-percent='30')
            span.skillbar-title(style='background: #a0d034;') PHP
            p.skillbar-bar(style='background: #b2ec2f;')
            span.skill-bar-percent
        .clearfix  
    // //stats
    // services
    #services.services
      .container
        h3.w3l-title Otros
        .box2
          .col-sm-4.s-1
            a(href='#')
              .view.view-fifth
                i.fa.fa-laptop(aria-hidden='true')
                .mask
                  i.fa.fa-laptop(aria-hidden='true')
                  h4 Photoshop
                  p Es un editor de gráficos rasterizados desarrollado por Adobe Systems Incorporated. Usado principalmente para el retoque de fotografías y gráficos.
                h3 Photoshop
          .col-sm-4.s-1
            a(href='#')
              .view.view-fifth
                i.fa.fa-clone(aria-hidden='true')
                .mask
                  i.fa.fa-clone(aria-hidden='true')
                  h4 Corel Draw
                  p Es un software de edición gráfica avanzado, que incluye diversos tipos de funciones de alteración y transformación de imágenes y páginas.
                h3 Corel Draw
          .col-sm-4.s-1
            a(href='#')
              .view.view-fifth
                i.fa.fa-pencil(aria-hidden='true')
                .mask
                  i.fa.fa-pencil(aria-hidden='true')
                  h4 Blender
                  p Es un software dedicado especialmente al modelado, iluminación, renderizado, animación y creación de gráficos tridimensionales.
                h3 Blender
          .clearfix
    // //services
    // interests
    .intra-w3l
      .container
        h3.w3l-title Intereses
        .agile-w3l-in
          i.fa.fa-camera(aria-hidden='true')
          p FOTOGRAFÍA
        .agile-w3l-in
          i.fa.fa-users(aria-hidden='true')
          p REDES SOCIALES
        .agile-w3l-in
          i.fa.fa-book(aria-hidden='true')
          p LEER
        .agile-w3l-in.w3l-intra-re
          i.fa.fa-gamepad(aria-hidden='true')
          p JUEGOS
        .agile-w3l-in.w3l-intra-re
          i.fa.fa-music(aria-hidden='true')
          p MUSICA
    // //interests
    // experience
    #experience.services-w3l
      .container
        h3.w3l-title Educación
        .wthree_latest_albums_grids
          .cntl
            span.cntl-bar.cntl-center
              span.cntl-bar-fill
            .cntl-states
              .cntl-state
                .cntl-content
                  h4 2002 - 2008
                  p Escuela Primaria "Julio López Domínguez"
                .cntl-image
                  img.img-responsive(src='images/primaria-general-slide.png', alt=' ')
                  .w3ls_cntl_image_pos
                    
                .cntl-icon.cntl-center 01
              .cntl-state
                .cntl-content
                  h4 2008 - 2011
                  p TELESECUNDARIA "LÁZARO CÁRDENAS DEL RÍO"
                .cntl-image.w3_cntl_image
                  img.img-responsive(src='images/secundaria-1.png', alt=' ')
                .cntl-icon.cntl-center 02
              .cntl-state
                .cntl-content
                  h4 2011 - 2014
                  p PREPARATORIA
                .cntl-image
                  img.img-responsive(src='images/cbtislogo-01.jpg', alt=' ')
                  .w3ls_cntl_image_pos
                    p Centro de Bachillerato Tecnológico Industrial y de Servicios N. 48
                .cntl-icon.cntl-center 03
              .cntl-state
                .cntl-content
                  h4 2014 - Actual 
                  p UNIVERSIDAD
                .cntl-image
                  img.img-responsive(src='images/ITSA2509_Aniversario 1.jpg', alt=' ')
                  .w3ls_cntl_image_pos
                    p Instituto Tecnológico Superior de Acayucan
                .cntl-icon.cntl-center 04
    // //experience
    // education
    #education.experience
      .container
        h3.w3l-title Mi Experiencia
        .col-md-12.abt-left
          .accordion
            .accordion-section
              h5
                a.accordion-section-title(href='#accordion-1')
                  span Diciembre 2017 - Enero 2018
                  | Ferretianguis
                  i.glyphicon.glyphicon-chevron-down
              #accordion-1.accordion-section-content
                h6 Actividad
                ul
                  li
                    span.glyphicon.glyphicon-arrow-right(aria-hidden='true')
                    a(href='#') Auxiliar en Ventas
                  
                  
            
    // //experiencie
    // projects
    #projects.portfolio
      .container
        h3.w3l-title Aptitudes
        .agileits_portfolio_grids
          .col-md-3.agileits_portfolio_grid
            .agileinfo_portfolio_grid.hovereffect
              a.cm-overlay(href='images/g2.jpg')
                img.img-responsive(src='images/g2.jpg', alt=' ')
                .overlay
                  h4 Organizado
            
            
          .col-md-3.agileits_portfolio_grid
            .agileinfo_portfolio_grid.hovereffect
              a.cm-overlay(href='images/g12.jpg')
                img.img-responsive(src='images/g12.jpg', alt=' ')
                .overlay
                  h4 Creativo
            
            
          .col-md-3.agileits_portfolio_grid
            
           
            .agileinfo_portfolio_grid.hovereffect
              a.cm-overlay(href='images/g9.jpg')
                img.img-responsive(src='images/g9.jpg', alt=' ')
                .overlay
                  h4 Responsable
          .col-md-3.agileits_portfolio_grid
            
            .agileinfo_portfolio_grid.hovereffect
              a.cm-overlay(href='images/g11.jpg')
                img.img-responsive(src='images/g11.jpg', alt=' ')
                .overlay
                  h4 Dispuesto a aprender
            
          .clearfix  
    // //projects
    // introduce
    .confi-w3l
      .container
        h3 Hola!
        p Mi nombre es Hugo Yadiel Ficachi Hernández, tengo 21 años de edad, y actualmente vivo en Soconusco, Veracruz. Estudio en el ITSA, curso el 8 semestre de la carrera de Ingeniería en Sistemas Computacionales.
        p
          | Mi objetivo es desarrollar mejores aptitudes durante la estancia en la empresa y poder colaborar en las actividades que se realizen.
    // //introduce
    
    // footer
    .footer.w3ls
      .container
        .w3ls-social-icons-2
          a.facebook(href='https://www.facebook.com/yadiel.ficher')
            i.fa.fa-facebook
          a.instagram(href='https://www.instagram.com/yadiel_ficachi.19/')
            i.fa.fa-instagram
          a.trello(href='https://trello.com/yadielficachi/')
            i.fa.fa-trello
          a.github(href='https://github.com/YadielFicachi')
            i.fa.fa-github
    .copyrights
      p
        | © 2018 CV | Diseñado por 
        a(href='http://') Hugo Yadiel
    // //footer
    // js-scripts
    // js
    script(type='text/javascript', src='/javascripts/jquery-2.1.4.min.js')
    script(type='text/javascript', src='/javascripts/bootstrap.js')
    // Necessary-JavaScript-File-For-Bootstrap
    // //js
    // start-smoth-scrolling
    script(type='text/javascript', src='/javascripts/move-top.js')
    script(type='text/javascript', src='/javascripts/easing.js')
    script(type='text/javascript').
      jQuery(document).ready(function($) {
      $(".scroll").click(function(event){
      event.preventDefault();
      $('html,body').animate({scrollTop:$(this.hash).offset().top},1000);
      });
      });
    // start-smoth-scrolling
    // for-bottom-to-top smooth scrolling
    script(type='text/javascript').
      $(document).ready(function() {
      /*
      var defaults = {
      containerID: 'toTop', // fading element id
      containerHoverID: 'toTopHover', // fading element hover id
      scrollSpeed: 1200,
      easingType: 'linear'
      };
      */
      $().UItoTop({ easingType: 'easeOutQuart' });
      });
    a#toTop(href='#', style='display: block;')
      span#toTopHover(style='opacity: 1;')  
    // //for-bottom-to-top smooth scrolling
    // menu-script
    script.
      (function($){
      // Menu Functions
      $(document).ready(function(){
      $('#menuToggle').click(function(e){
      var $parent = $(this).parent('.menu');
      $parent.toggleClass("open");
      var navState = $parent.hasClass('open') ? "hide" : "show";
      $(this).attr("title", navState + " navigation");
      // Set the timeout to the animation length in the CSS.
      setTimeout(function(){
      console.log("timeout set");
      $('#menuToggle > span').toggleClass("navClosed").toggleClass("navOpen");
      }, 200);
      e.preventDefault();
      });
      });
      })(jQuery);
    // //menu-script
    // baneer-js
    script(src='/javascripts/responsiveslides.min.js')
    script.
      // You can also use "$(window).load(function() {"
      $(function () {
      // Slideshow 4
      $("#slider").responsiveSlides({
      auto: true,
      pager:false,
      nav:false,
      speed: 500,
      namespace: "callbacks",
      before: function () {
      $('.events').append("<li>before event fired.</li>");
      },
      after: function () {
      $('.events').append("<li>after event fired.</li>");
      }
      });
      });
    // //baneer-js
    // skills
    script(src='/javascripts/skill.bars.jquery.js')
    script.
      $(document).ready(function(){
      $('.skillbar').skillBars({
      from: 0,
      speed: 4000,
      interval: 100,
      decimals: 0,
      });
      });
    // //skills
    // timeline
    script(type='text/javascript', src='/javascripts/jquery.cntl.js')
    script(type='text/javascript').
      $(document).ready(function(e){
      $('.cntl').cntl({
      revealbefore: 300,
      anim_class: 'cntl-animate',
      onreveal: function(e){
      console.log(e);
      }
      });
      });
    // //timeline
    // accordion
    script.
      jQuery(document).ready(function() {
      function close_accordion_section() {
      jQuery('.accordion .accordion-section-title').removeClass('active');
      jQuery('.accordion .accordion-section-content').slideUp(300).removeClass('open');
      }
      jQuery('.accordion-section-title').click(function(e) {
      // Grab current anchor value
      var currentAttrValue = jQuery(this).attr('href');
      if(jQuery(e.target).is('.active')) {
      close_accordion_section();
      }else {
      close_accordion_section();
      // Add active class to section title
      jQuery(this).addClass('active');
      // Open up the hidden content panel
      jQuery('.accordion ' + currentAttrValue).slideDown(300).addClass('open');
      }
      e.preventDefault();
      });
      });
    // //accordion
    // for projects
    script(src='/javascripts/jquery.tools.min.js')
    script(src='/javascripts/jquery.mobile.custom.min.js')
    script(src='/javascripts/jquery.cm-overlay.js')
    script.
      $(document).ready(function(){
      $('.cm-overlay').cmOverlay();
      });
    // //for projects
    // smooth scrolling
    script(src='javascripts/SmoothScroll.min.js')
    // //smooth scrolling
    // //js-scripts`

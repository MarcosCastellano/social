<style type="text/css">
        	@keyframes slideDown {
			    0% {
			        transform: translateY(-150%);
			        opacity: 0;
			    }
			    100% {
			        transform: translateY(0);
			        opacity: 100%;
			    }
			}
            html, body, div {
                margin: 0;
                padding: 0;
                border: 0;
                font-size: 100%;
                font: inherit;
                vertical-align: baseline;
            }
            body {
                line-height: 1.2;
                font-family: Arial, Helvetica, sans-serif;
                text-align: center;
                background-color: #fff;
                color: rgba(0, 0, 0, 0.76);
            }
            a {
                text-decoration: none;
                color: rgba(0, 0, 0, 0.76);
            }
            a:hover {
                color: rgba(0, 0, 0, 1);
            }
            ::selection {
                background: #fff;
            }
            ::-moz-selection {
                background: #fff;
            }
            #name {
                font-size: 45px;
                font-weight: 700;
                margin-top: 135px;
                animation: 1s ease-out 0s 1 slideDown;
            }
            #job {
                font-size: 25px;
                font-weight: bold;
                margin-top: 35px;
                padding: 0 15px;
                animation: 1s ease-out 0s 1 slideDown;
            }
            #corporation {
                font-family: Verdana;
                font-weight: normal;
                font-style: italic;
            }
            #contact {
                font-size: 20px;
                font-weight: 300;
                font-style: italic;
                margin-top: 35px;
                animation: 1s ease-out 0s 1 slideDown;
            }
            #ilogeek{
                margin: 60px auto 15px;
                animation: 1s ease-out 0s 1 slideDown;
            } #ilogeek img {
            	width: 150px;
            }
            #tecladostop {
                animation: 1s ease-out 0s 1 slideDown;
            } #tecladostop img {
                width: 190px;
            }
			@media (max-width: 700px) {
				#name {
	                font-size: 30px;
	            }
	            #job {
	                font-size: 20px;
	            }
	            #contact {
	                font-size: 15px;
	            }
	            #ilogeek img {
	                width: 110px;
	            }
			}
        </style>
    </head>
    <body>
        <div id="name">Jorge Sánchez López</div>
        <div id="job">E-commerce IT operations manager in <br><span id="corporation">Carrefour Spain</span></div>
        <div id="contact">
            <a href="mailto:hola@jsanchez.me" title="Mail">Mail</a>
            &#10022;
            <a rel="me" href="https://mastodon.world/@jsanchez0x" title="Mastodon">Mastodon</a>
            &#10022;
            <a href="https://www.linkedin.com/in/jsanchez0x" title="LinkedIn">LinkedIn</a>
            &#10022;
            <a href="https://github.com/jsanchez0x" title="GitHub">GitHub</a>
        </div>
    </body>
</html>

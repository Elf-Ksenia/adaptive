<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>MailGenius</title> 
  <link href="https://fonts.googleapis.com/css2?family=PT+Sans:wght@400;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://unpkg.com/aos@next/dist/aos.css" />
  <link rel="stylesheet" href="css/slicknav.css">
  <link rel="stylesheet" href="css/style.css">
  
</head>

<body>
  <header class="header" data-aos="fade-in" data-aos-easing="ease-in-out" data-aos-duration="1000">
    <div class="container d-flex align-items-center justify-content-btw">
      <a href="#" class="logo hvr-grow">
        <img src="img/logo.png" alt="logo">
      </a>
      <div class="header-nav d-flex align-items-center justify-content-btw">
      <nav class="main-header-nav">
        <a href="#" class="hvr-grow">Email Consulting</a>
        <a href="#" class="hvr-grow">Contact Us</a>
      </nav>
      <nav class="info-header-nav">
        <a href="#" class="hvr-grow">Privacy Policy</a>
        <a href="#" class="hvr-grow">Disclaimer</a>
      </nav>
    </div>
  </div>
    <!-- container -->
  </header>
  <!-- header -->
  <main class="main">
    <section class="process-screen">
      <div class="container d-flex align-items-center">
        <div class="process-screen-content d-flex flex-direction-column">
          <div class="process-screen-body">
            <form class="action-form d-flex flex-direction-column align-items-center">
              <h1 class="big-num">98<sup class="underline-num">/100</sup></h1>
              <h2 class="result-title">MailGenius Score</h2>
              <p class="result-text">
                We’ve found 2 things you can do to avoid landing in the spam folder and increase security.
              </p>
              <div class="checkbox-container">
                <div class="checkbox-group d-flex align-items-center">
                  <div class="checkbox-item hvr-box-shadow-inset">
                    <input type="checkbox" name="things-to-fix" id="things-to-fix">
                    <label class="checkbox-label left  hvr-icon-buzz-out" for="things-to-fix"><i class="fas fa-exclamation-triangle  hvr-icon"></i>2 Things to fix</label>
                  </div>
                  <div class="checkbox-item hvr-box-shadow-inset">
                    <input type="checkbox" name="passing-tests" id="passing-tests">
                    <label class="checkbox-label center hvr-icon-bounce" for="passing-tests"><i class="fas fa-thumbs-up hvr-icon"></i>11 Passing tests</label>
                  </div>
                  <div class="checkbox-item hvr-box-shadow-inset">
                    <input type="checkbox" name="email-preview" id="email-preview">
                    <label class="checkbox-label right hvr-icon-push" for="email-preview"><i class="fas fa-envelope hvr-icon"></i>Email preview</label>
                  </div>
                </div>
                <div class="checkbox-comments d-flex justify-content-btw">
                  <span class="">Sorted by: Important</span>
                  <span class="">Share these results: <b
                      class="text-green">mailgenius.com/spam-test/example-1</b></span>
                </div>
              </div>
            </form>
            <!-- action-form -->

            <div class="process-scenarius">
              <div class="process-scenarius-header could-be-better">
                <div class="scenarius-container">
                  <span class="list-num active">1</span>
                  <h3><svg data-aos="zoom-in" data-aos-duration="1000" width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                      <path
                        d="M12 0C5.38 0 0 5.38 0 12C0 18.62 5.38 24 12 24C18.62 24 24 18.62 24 12C24 5.38 18.62 0 12 0ZM5 9.07C5 7.96 5.9 7.07 7 7.07C8.1 7.07 9 7.96 9 9.07C9 10.17 8.1 11.07 7 11.07C5.9 11.07 5 10.17 5 9.07ZM15.25 18.25H8.75C8.198 18.25 7.75 17.802 7.75 17.25C7.75 16.698 8.198 16.25 8.75 16.25H15.25C15.802 16.25 16.25 16.698 16.25 17.25C16.25 17.802 15.802 18.25 15.25 18.25ZM17 11.07C15.9 11.07 15 10.17 15 9.07C15 7.96 15.9 7.07 17 7.07C18.1 7.07 19 7.96 19 9.07C19 10.17 18.1 11.07 17 11.07Z"
                        fill="white" />
                    </svg>Could be Better - Your email is missing the List-Unsubscribe header.</h3>
                </div>
              </div>
              <div class="scenarius-container">
                <p class="scenarius-description">
                  Severity of this problem: <b>Low</b><br>
                  Estimated time for you to fix it: <b>120 minutes</b>
                </p>
                <h4 class="scenarius-title">Why is this important?</h4>
                <p class="scenarius-text result-text">Spam complaints are the #1 factor that will hurt your email
                  deliverability. Including an easy unsubscribe mechanism effectively helps prevent these spam
                  complaints.
                  Email Service Providers and spam filters also view it favorably when they make inboxing decisions.</p>
                <h4 class="scenarius-title">Problems you can fix:</h4>
                <h5 class="scenrius-subtitle text-green">(-1 points) There is no List-Unsubscribe header.</h5>
                <p class="text-small">Solution:</p>
                <p class="scenarius-text result-text">Using an email tool that allows you to alter email headers, add
                  the
                  List-Unsubscribe header with the appropriate mailto and/or link for receivers to unsubscribe with.</p>
                <div class="scenarius-buttons">
                  <button class="btn btn-light hvr-box-shadow-inset ">Learn more about list-unsubscribe header</button>
                  <button class="btn btn-light hvr-box-shadow-inset ">Get help fixing this</button>
                </div>
              </div>
            </div>
            <!-- /.process-scenarius -->
            <div class="process-scenarius">
              <div class="process-scenarius-header good">
                <div class="scenarius-container">
                  <span class="list-num active">2</span>
                  <h3><svg data-aos="zoom-in-up" width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                      <path
                        d="M12 24C18.617 24 24 18.617 24 12C24 5.383 18.617 0 12 0C5.383 0 0 5.383 0 12C0 18.617 5.383 24 12 24ZM17 7.065C18.103 7.065 19 7.962 19 9.065C19 10.168 18.103 11.065 17 11.065C15.897 11.065 15 10.168 15 9.065C15 7.962 15.897 7.065 17 7.065ZM7 7.065C8.103 7.065 9 7.962 9 9.065C9 10.168 8.103 11.065 7 11.065C5.897 11.065 5 10.168 5 9.065C5 7.962 5.897 7.065 7 7.065ZM3.646 14.305C3.788 14.113 4.012 14 4.25 14H19.75C19.988 14 20.212 14.113 20.354 14.305C20.495 14.497 20.537 14.744 20.466 14.972C19.306 18.709 15.904 21.22 12 21.22C8.096 21.22 4.693 18.709 3.534 14.972C3.463 14.745 3.505 14.497 3.646 14.305Z"
                        fill="white" />
                    </svg>Good - Your email is missing the List-Unsubscribe header.</h3>
                </div>
              </div>
              <div class="scenarius-container">
                <p class="scenarius-description">
                  Severity of this problem: <b>Low</b><br>
                  Estimated time for you to fix it: <b>30 minutes</b>
                </p>
                <h4 class="scenarius-title">Why is this important?</h4>
                <p class="scenarius-text result-text">Without having a Requested Mail Receiver DMARC policy published,
                  emails from your domain can be spoofed and sent on your behalf.</p>
                <h4 class="scenarius-title">Problems you can fix:</h4>
                <h5 class="scenrius-subtitle text-green">(-1 points) Your DMARC record policy is set to none.</h5>
                <p class="text-small">Solution:</p>
                <p class="scenarius-text result-text">You may want to set your DMARC record to have a policy of reject
                  or quarantine. A policy of none results in no action when an email from your domain fails the DMARC
                  mechanism, allowing spoofers to act more freely.
                </p>
                <p class="scenarius-text result-text">Before making this change it is important to understand that a
                  policy other than none can result in legitimate email being sent to spam. If anyone sending from this
                  domain fails an Email Service Provider's DMARC check, only a none policy will allow the mail to reach
                  to the inbox. This also includes anyone who is fraudulently sending from this domain. This is why it
                  is important to make sure your DMARC, DKIM, & SPF authentication is properly setup for all senders of
                  your domain including all email tools you are using before employing a stricter policy of either
                  reject or quarantine.
                </p>
                <p class="scenarius-text dns">Existing DNS Records:</p>
                <p class="scenarius-text result-text">_dmarc.gmail.com. 60 IN TXT v=DMARC1; p=none; sp=quarantine;
                  rua=mailto:mailauth-reports@google.com</p>
                <p class="scenarius-text result-text">Note: You can only edit these records when sending from a custom
                  domain.</p>
                <div class="scenarius-buttons">
                  <button class="btn btn-light hvr-box-shadow-inset ">Learn more about dmarc</button>
                  <button class="btn btn-light hvr-box-shadow-inset ">Get help fixing this</button>
                </div>
              </div>
            </div>
            <!-- /.process-scenarius -->
            <div class="process-scenarius badly">
              <div class="process-scenarius-header badly">
                <div class="scenarius-container">
                  <span class="list-num active">3</span>
                  <h3><svg data-aos="zoom-out" data-aos-duration="1000" width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                      <path
                        d="M12 0C5.38 0 0 5.38 0 12C0 18.62 5.38 24 12 24C18.62 24 24 18.62 24 12C24 5.38 18.62 0 12 0ZM5 9.07C5 7.96 5.9 7.07 7 7.07C8.1 7.07 9 7.96 9 9.07C9 10.17 8.1 11.07 7 11.07C5.9 11.07 5 10.17 5 9.07ZM17.707 18.743C17.512 18.938 17.256 19.036 17 19.036C16.744 19.036 16.488 18.938 16.293 18.743C15.147 17.596 13.622 16.965 12 16.965C10.378 16.965 8.854 17.596 7.707 18.743C7.316 19.134 6.684 19.134 6.293 18.743C5.902 18.353 5.902 17.72 6.293 17.329C7.817 15.805 9.844 14.965 12 14.965C14.156 14.965 16.183 15.805 17.707 17.329C18.098 17.719 18.098 18.353 17.707 18.743ZM17 11.07C15.9 11.07 15 10.17 15 9.07C15 7.96 15.9 7.07 17 7.07C18.1 7.07 19 7.96 19 9.07C19 10.17 18.1 11.07 17 11.07Z"
                        fill="white" />
                    </svg>
                    </svg>Badly - Your email is missing the List-Unsubscribe header.</h3>
                </div>
              </div>
              <div class="scenarius-container">
                <p class="scenarius-description">
                  Severity of this problem: <b>Low</b><br>
                  Estimated time for you to fix it: <b>120 minutes</b>
                </p>
                <h4 class="scenarius-title">Why is this important?</h4>
                <p class="scenarius-text result-text">Spam complaints are the #1 factor that will hurt your email
                  deliverability. Including an easy unsubscribe mechanism effectively helps prevent these spam
                  complaints.
                  Email Service Providers and spam filters also view it favorably when they make inboxing decisions.</p>
                <h4 class="scenarius-title">Problems you can fix:</h4>
                <h5 class="scenrius-subtitle text-green">(-1 points) There is no List-Unsubscribe header.</h5>
                <p class="text-small">Solution:</p>
                <p class="scenarius-text result-text">Using an email tool that allows you to alter email headers, add
                  the
                  List-Unsubscribe header with the appropriate mailto and/or link for receivers to unsubscribe with.</p>
                <div class="scenarius-buttons">
                  <button class="btn btn-light hvr-box-shadow-inset ">Learn more about list-unsubscribe header</button>
                  <button class="btn btn-light hvr-box-shadow-inset ">Get help fixing this</button>
                </div>
              </div>
            </div>
            <!-- /.process-scenarius -->
          </div>
          <!-- process-screen-body -->
        </div>
        <!-- process-screen-content -->
        <div class="helpfull-links">
          <ul class="links-list">
            <li class="links-list-tile" data-aos="fade-down">helpfull links</li>
            <li class="links-list-item" data-aos="fade-down" data-aos-delay="100"><a href="#" class="hvr-grow">live chat</a></li>
            <li class="links-list-item" data-aos="fade-down" data-aos-delay="200"><a href="#" class="hvr-grow">partners & discounts</a></li>
            <li class="links-list-item" data-aos="fade-down" data-aos-delay="300"><a href="#" class="hvr-grow">free 15 minnutes call</a></li>
          </ul>
          <button class="btn gradient-btn hvr-bob" data-aos="fade-down" data-aos-delay="400" >New email test</button>
          <div class="img" data-aos="fade-down" data-aos-delay="500"><svg width="134" height="11" viewBox="0 0 134 11" fill="none" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
            <rect width="134" height="11" fill="url(#pattern0)"/>
            <defs>
            <pattern id="pattern0" patternContentUnits="objectBoundingBox" width="1" height="1">
            <use xlink:href="#image0" transform="translate(-0.000746269) scale(0.00328358 0.04)"/>
            </pattern>
            <image id="image0" width="305" height="25" xlink:href="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAATEAAAAZCAYAAABZ7RmHAAANJUlEQVR4Ae2cwY4ctxGGyd0ggCwD0SannLx+Aq+lB/D6HsCbU46WTrnF62NOWj2B5Jxyk3TMydILRBaQa2T5AYJID2BtDGit5KCp4GsXRzW1JLvZPT07gtXAYNjdZFWxyPpZVc3uGN4d7zSwIQ2IyH4I4YPELsb4OJXf/bdpQESuhBA+Mq2+izH+x5z/bIpRRO44ZdyPMd5r0YCIHIQQbps2RRqZuqbZsGKM8dNUU0SQdWkYIYSHMUb61HSIyPUQwuem0fMYI9eWh4h8E0KQ5YX2wpcxxqe+WYa3r2LPac9k/aYFBBp4QBsez0IIj2OM/I861NDQ6VEI4bBABF7o9asWXpl5hBEfF3icu5zRR3ZsaJixEWR9cI5o5UKGX9FGSmSUxmeqS0DMH4wdckEbnRYPEflDCOGvxQrTbtxKNnh2eu1IJHwxjVyldZT7vwghAECfmGqHIvI0Z2ymji+iUDtJayusr+tptZ4zWHdNI/rTDGIhhBMHhrcMzVS0ekrXWv5zE4/2eChWfzWay3oiHZ4C4kyaPrBp4QHodIcuEhh40yovIuiTyVvqc2LBePE7buTl51FMBAf+e33U5PQ2ciAizxptxPOr2chKF0SE8cBJgEbtoA8svNd1wb1RmRe/HTA2NV6lez8kAOsqiNyOIfbJXaLVf30RHu8Uaj3SVbRwe6sus/L8YCS6oiuWuVQv6iSx3hwNmrzROodZ7zJpv1XPZA5G0P+3hoK99Jk3IvJ1COHmCCOZuy+98g+sAFjc3YSNqBeIPluBgMWOebFckAb2bWq1PyYCP55ePQ5zApgywhPLHQzSoxDCx7mb23QND0FEADIbClJuASGMxx6EpH2eja2/7vJzDedydPEKfuVuMF5M9A/d9drpdxqW2jrQsXmWdK8z2hDCMoxPN+y/GjXzBhn98VDDxhROJ88EI7P94TqL6KeNno7nN/c5fcQ7ujEXI/VM7by2rPDkUmqB8fHeInW7eaG6rIaXlvCEMhHc32gvpwdXziTcbHWPR/HG7ZTyMSgsExFCUHsQSmSPTN3JysULscy1nDOkczLhYWTaZlcvX+8csZEXCL0c7aL+YKEy+zaQKOaEMjyWYakXW+k/cDJxWtUpRpdpA52iF6GeW64vpzVPZ+o8atRHzUaKOrd6zfDrG+OcTliwuQ44ZQ+9T710ZHN3zJVUQf+b0gVZ5jNdfHV6cPjyxbVHZy+uybnf91dPSuFkEueL1tAsNdzkv67YeBb2GDS5yMXYRiEEEvrZgXf1LuwULzHGiBH4vF0RmFqEVfoAOR6hPYr0M4lr2pFgPqp5tXjS2pff+7TAyNymlXcT5dsA6joZ6WJBOG4P5vcBuqrlJ1WXLDbU5+ejDEtzq8sJvBay+yhWcsY5EPMTl0GqrsBbognvNX5WW7GMzH6QPR1TdeuKHmx9Xm+qwN5LLnoA+mDE8iMk97q191fKunD4BeXzdQPECtPxJzYHC5WvB861oRz9HMQmD2uLgSWs9QBW2myth2VltuWh4JXa5HJiTCSUmAwixdUfb7lCMGjkTvkV5MaI/IRIfScs436qn6635NJSmwv5xwPVJ5SJ/7oXGw9aWYPIPBjByAcDWBKerT06JvYpMHQ8mKYmF/WfbCTNHfS0lhyyht62//TxeqvttdYPIfxSRP40RqExxr+MaefbAF6vZffmQsJhPpcmz0XCgxjjypaNHIgxUQklmDhpkMhpsI0Bl38rDwYtk+Cns0UQy4SShD9ZQ93GTmdWfx9SjxZbvW9vTN7zS/R9OHVvgh4JkwGEdHgZ0vWL/OehDzZi5SQvezfGODXR7/Ox7H/bBIhfYq/eCKWyYHUgRjL/R9m9uxNff3Vp7+lgmQeBVwwn7+89uUfdheyugFgunAyaY/Ku/RFJwxGd3GQTLx9Je29gnTxqpP5J3FvjhalSfd9aAPgjEfkk8yOEY8HCQK0nVtuM6j3AwRPYTw41WBuuMYbFBwO+/abOVU6fk2R/VrMH6mT2Y7rtc/J3Sf6zxQ72d0QOq0vEnx6wMbd49IeN8lyi3Lj86yf7AFiJUM4T6+qqa8/ktKh3UzfCllbkEp/adQxp6C54dpD7QV7SJhcgIjx6tqs3YJwzKg/SJPRz9Zb0faFBbhaGvIfsiQ48Vy/MJ39b5K95qF4KNtP6BcLW8SDTIoelk8psHbBjCP2L3PKS5Fr5Rye6GFpjJYfculnc0rULB9fTlhRbZ1vK9PMfCPPy9OAgypswr0vEy+7h2YurzyTGk/f3/nk/CU3dILu3q2Gjel6pTe2/CGI04jUO9WSsx8ImP4TfukmlHQWxrQGQ4N+38ioA+P03LUZd0+ls91RuxoLFBRD24DFHHwCkvkUr5U+7vk8IJWfT3YyEU84u2QggRKJ/23PIXiX/DSH82V/sOWdvYnfshJ3DvCcS96OEe2cvrp4AZnEhh0FKD3zwvH4KGxPdIf9VEFMCeD4AVsqPpUFiM2JL+DJEnsl11IPEmJO80GSiWU8i5/IX3dXJQrUTwOP1XlYfFV4xmWM8GH92fqOf0utHhH9LfQO2M8nSp4ON36efGkIC9kkHLC4YeHVz8MaFrTP838rrQvW65+6+t/fkzqvTgweLxe6JxHAU3+hC6/4EZiEbkIwDryREL4jpIHUTOTVST2Bdu5V5fDwUQIZ6f9CzYTBlC2I+lByb0Pc5EaOijRYBsKE6TIJ9WQhVMEB+eHs2TAL4uZ4zTB/+0XZKSEl7ewwdd9umr+x59NUv3tenxMwp+w4vG8DZ02XnXZFG5cZUXVZIr/fWpb2njNP1LsG/2DkOEechrnjplqPwumCU41q+y9YvlXtBjIY6SEx6+6UKkpg8OZkawqSNmyUZx1xHJgti3fuU6qUByF6xo/qwhgk6pm+2DXkGDGWMkZMSqAKN5nush4FhsnnVh5fwtyF8erptZR1UVp7Jo6ENLxTn+jfV6/S5p0HylSqtMYeMvq0uSXuMmp8lWee+HveeMjaA98nL06vXo1B+A2aAVxS5c3lncUfrThIp+3QyR1HBapmc0zpbuRFWJ73/SkDKgXkvDCDetuQpsuPl2Z/XPUMwa26y8JSaRcAfHtR4wjkWJLzn4ml3vDNjZg3fy5c7955YDihz7YrX9FNAfpsLOWTPq0gjk39k60ZO5zUaW3MPL4unizvxNR78wyBy63J8vX/5N09O1gFgdHSQJ2Y0AgAwICmJyS0exU/dG2NYrK1IeGUndudFuBAJZtu4yvGtMG/MbM4FGGyIxyJC3TlB2Bv3OYPEMxMR0gLJw0XO5nSDbpq1/WN8amEygLGci+SmhoTVysd6ezyZ9v0cOxEBHGgl+uiCMNMvqln6jKXTJfUY56Yc9LblJXXfWNXzzypkwMXBnhi0NFlLbsTu40mDNIDd5qroZPavUNmcBcLQj+xKvzlJmzh53dN43a+8eIHIgw05POiSbrDphyoN9Vb8+LClpjbx/dhh7MzH4qH3vVw1HkVauRtqI95zAvhTJJBr5q/5aIH2gz+Ppbrk80m5B1ie11t/3gRi9FZXfa+c6sS5QC35VdzLySsMU3MrG+ueyup3dAMy3ijXIpMavM0tQjfr9emiwed27MEWHUC2CoT69Y1v3eZaFhg/zyxtynjRfkHF2LP8tD9EDv6+B2DPp+lcbYQcsj383LP3Vsqac/S6BMiq3wejf/pUO+mSULZPhyu838aT1nCy66OGD+RrWrcB5HT0wYjtBH0rdOIDiNVknBRKjpCbsMUDa5J10D+eiYjweogFF7wedNJCm7yVDbc9f4zGAyZ1ajrDYPBqliGe0iCUx2ving3boM/Pgwp8el94BtT1LRIL4snYLT/o4x3By4PJkK/iet30npNDVo+oxQOzdHO6pB8sCuiQ/tkFuDRebMgdslhfFpG/WwFcmSfgXWTDJ6dDEDvGrup8p4tF2A9u2/goEENE3a3MxKgZwpDeMDCtKyEA2hsCkOcQEVY0n2dBrnUk9FvlJi/SAjRZ/RU2Iaf8mAWJbHu9OGaFrhq8ggpzAgOz8wLggN8QnnhWAFjW4/MdKoDFUH5srWkdQy9C7TyXQ67VX96r6JI62IwPOZdtTYGc4dAvWYAFue0zkPtXArBXpwf7r3lHNES/GBi2MxYdgMGpOZx04rGy+byTq3LhpyXQqHkUFy70AAEABB9KLXdQD2jfWqXv1aOOHsanr4ax0Fj5hvDjCSxvVwwCsERQP/kDv5aD/gwB1RaaK3XRhXp/rXro6EzUJd76UABbkTtzstQTm1kvDMAygnFpEohNHaSCTGu9rPkFD7TsPSqB21r5z0VMDd17ETyOXyc4s5JjDB+2eixaH4+B3JDfdmDVwtgAXjx9a/7kTCKk/Pg8N7RKoMF17jf3J/Fp/dennksQaG1PfaNLgLpPl2m8jtU+x7C0bUhTdO9H8sJ2iE0PKCyd2coZ52w2Xu8I/4w1oEl18jb2wGtr8rps41pZ81E25JmNV02OOe5tWpdz9GGdNP8PK1VuCftmg84AAAAASUVORK5CYII="/>
            </defs>
            </svg>
          </div>
          <h6 class="links-list-text" data-aos="fade-down" data-aos-delay="600">Pro Tip: Always verify your email lists.</h6>
          <h6 class="links-list-text text-green" data-aos="fade-down" data-aos-delay="700"><b>10% discount on NeverBounce</b></h6>
        </div>
        <!-- /.helpfull-links -->
      </div>
      <!-- container -->
    </section>
    <!-- /.process-screen -->
    <section class="footer">
      <div class="container d-flex align-items-center">
        <img src="img/image 17.png" alt="">
        <div class="footer-text">
          <p>Pro Tip: Always verify your email lists.<br>
            <span>10% discount on NeverBounce</span>
          </p>
        </div>
      </div>
      <!-- /.container -->
    </section>
    <!-- footer -->
  </main>
  <script src="https://kit.fontawesome.com/0e45e18164.js" crossorigin="anonymous"></script>
  <script src="https://code.jquery.com/jquery-3.5.1.min.js" integrity="sha256-9/aliU8dGd2tb6OSsuzixeV4y/faTqgFtohetphbbj0=" crossorigin="anonymous"></script>
 
<script src="js/jquery.slicknav.min.js"></script>
  <script>
    $(function(){
        $('.header-nav').slicknav({
  appendTo: '.header .container',
  label: ''
        });
    });
  </script>
   <script src="https://unpkg.com/aos@next/dist/aos.js"></script>
   <script>
     AOS.init();
   </script>
  
</body>

</html>

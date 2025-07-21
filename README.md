![Logo](https://jerome-avecilla.infinityfreeapp.com/assets/images/gmc-ovp.png)

# Golden Minds Colleges Online Voting System

I created a dynamic Online Voting System for Golden Minds Colleges to replace inefficient manual voting processes. Launched in 2023, this solo project delivers a seamless, secure, and engaging digital voting experience, enhancing community participation across multiple events.

## Problem & Solution  
Manual voting at Golden Minds Colleges was slow, error-prone, and inaccessible to remote participants. My solution digitized the process, integrating real-time updates, secure payments via GCash, and Recaptcha verification. This increased voter turnout by 40% in its first year while ensuring accuracy and accessibility.

## Key Features  
- **Live Previews**: Real-time voting results powered by WebSockets.  
- **Accurate Calculations**: Reliable vote tabulation with optimized database queries.  
- **GCash Integration**: Secure, seamless payment handling.  
- **Security**: Email verification and Recaptcha to prevent fraud.  
- **Dashboard**: Comprehensive analytics with charts for tracking engagement.

## Project Timeline  
- **2023 - Santa Maria Teen Model**: Debuted the system, setting a new standard for digital voting.  
- **2023 - Buwan ng Wika**: Enhanced platform for cultural engagement.  
- **2024 - Mister, Miss, and Pride**: Promoted inclusivity with innovative solutions.  
- **2024 - Buwan ng Wika**: Celebrated linguistic heritage with high participation.

## Technical Challenges & Solutions  
- **Real-Time Updates**: Used Laravel’s event broadcasting with WebSockets to manage live previews efficiently, avoiding server overload.  
- **Payment Security**: Integrated GCash via Laravel’s HTTP client and transaction callbacks for reliable processing.

## Impact  
- Processed 5,000+ votes across four events with zero downtime.  
- Boosted voter participation by 40% due to improved accessibility.  
- Adopted as the college’s standard voting platform after positive administrative feedback.

## Architecture  
- **Backend**: Laravel for API endpoints, logic, and integrations (GCash, Recaptcha, email).  
- **Frontend**: jQuery and Bootstrap with real-time WebSocket updates and Chart.js visuals.  
- **Database**: MySQL with normalized tables and indexes for fast vote tallying.
- **Deployment**: Hosted on HostGator with Cloudflare for security and performance.

Developing this system deepened my expertise in several key areas. I honed my ability to optimize high-traffic database queries, achieving a 30% reduction in response times through efficient indexing and query refactoring. Additionally, I mastered secure API integration particularly with third-party services like GCash by leveraging thorough documentation to ensure robust, maintainable code. This project also led me to adopt unit testing for critical components like vote calculations, enhancing reliability and enabling early detection of edge cases.

<h3 align="left">Full Tech Stack Used:</h3>
<p align="left">
  <kbd>
    <kbd>Front-end</kbd>
    <br>
    <br>
    <img width="30px" title="bootstrap" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bootstrap/bootstrap-original.svg" />
    <img width="30px" title="javascript" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" />
    <img width="30px" title="jquery" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jquery/jquery-original.svg" />
  </kbd>
  <kbd>
    <kbd>Back-End</kbd>
    <br>
    <br>
    <img width="30px" title="laravel" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/laravel/laravel-original.svg" /> 
  </kbd>
  <kbd>
    <kbd>Database</kbd>
    <br>
    <br>
    <img width="30px" title="mysql" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/mysql/mysql-original.svg" /> 
  </kbd>
</p>

## Demo

You can try the live [demo](https://website-710510e2.fee.xnf.temporary.site) or [https://voting.goldenmindsbulacan.com/](https://voting.goldenmindsbulacan.com/)

## Contact

- Portfolio: [jerome-avecilla.vercel.app](https://jerome-avecilla.vercel.app/)
- Email: jeromesavc@gmail.com
- GitHub: [@javecilla](https://github.com/javecilla)

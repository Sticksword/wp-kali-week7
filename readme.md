* Stored XSS in Wordpress Core for embed youtube urls:
  * created by adding crafted xss youtube embed url
  * WPScan summary:
    Title: WordPress  4.0-4.7.2 - Authenticated Stored Cross-Site Scripting (XSS) in YouTube URL Embeds
        Reference: https://wpvulndb.com/vulnerabilities/8768
        Reference: https://wordpress.org/news/2017/03/wordpress-4-7-3-security-and-maintenance-release/
        Reference: https://github.com/WordPress/WordPress/commit/419c8d97ce8df7d5004ee0b566bc5e095f0a6ca8
        Reference: https://blog.sucuri.net/2017/03/stored-xss-in-wordpress-core.html
        Reference: https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2017-6817
    [i] Fixed in: 4.2.13
  * helpful link: https://blog.sucuri.net/2017/03/stored-xss-in-wordpress-core.html

* Cross-Site Request Forgery in WordPress "Press This" function allows DoS: (ok now this one)
  * recreated by adding extremely large file at remote server and having php fetch it
  * WPScan summary:
    Title: WordPress 4.2-4.7.2 - Press This CSRF DoS
        Reference: https://wpvulndb.com/vulnerabilities/8770
        Reference: https://wordpress.org/news/2017/03/wordpress-4-7-3-security-and-maintenance-release/
        Reference: https://github.com/WordPress/WordPress/commit/263831a72d08556bc2f3a328673d95301a152829
        Reference: https://sumofpwn.nl/advisory/2016/cross_site_request_forgery_in_wordpress_press_this_function_allows_dos.html
        Reference: http://seclists.org/oss-sec/2017/q1/562
        Reference: https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2017-6819
    [i] Fixed in: 4.2.13
  * helpful link: http://seclists.org/oss-sec/2017/q1/562

* WordPress audio playlist functionality is affected by Cross-Site Scripting:
  * recreated by adding mp3 file to audio playlist in a post
  * WPScan summary:
    Title: WordPress 3.6.0-4.7.2 - Authenticated Cross-Site Scripting (XSS) via Media File Metadata
        Reference: https://wpvulndb.com/vulnerabilities/8765
        Reference: https://wordpress.org/news/2017/03/wordpress-4-7-3-security-and-maintenance-release/
        Reference: https://github.com/WordPress/WordPress/commit/28f838ca3ee205b6f39cd2bf23eb4e5f52796bd7
        Reference: https://sumofpwn.nl/advisory/2016/wordpress_audio_playlist_functionality_is_affected_by_cross_site_scripting.html
        Reference: http://seclists.org/oss-sec/2017/q1/563
        Reference: https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2017-6814
    [i] Fixed in: 4.2.13
  * helpful link: http://seclists.org/oss-sec/2017/q1/563

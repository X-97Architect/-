The basic syntax is dirb <url_base> <wordlist_file> [options].
• -i (Case Insensitive Search): By default, many web servers are case-sensitive. Using -i forces the tool to check for both /Admin and /admin.
• -a (User-Agent): This allows you to change the "Identity" the tool presents to the server. Attackers often change this to look like a standard browser (e.g., Mozilla or Chrome) to avoid being flagged by basic security filters.
• -p (Proxy): This routes your traffic through a proxy server. This is used to hide the origin IP address of the scan.
• -X (Extension Search): This is one of the most useful commands for finding specific files. You can tell the tool to look for specific file extensions.
• Example: dirb http://localhost/ -X .html,.php,.txt
• This will append those extensions to every word in the list.

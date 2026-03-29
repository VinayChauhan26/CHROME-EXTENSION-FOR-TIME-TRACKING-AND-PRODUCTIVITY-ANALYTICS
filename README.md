# CHROME-EXTENSION-FOR-TIME-TRACKING-AND-PRODUCTIVITY-ANALYTICS

"COMPANY":CODTECH IT SOLUTIONS

"NAME":VINAY CHOUHAN

"INTERN ID":CTIS7061

"DOMAIN":FULL STACK DEVELOPMENT

"DURATION":4 WEEKS

"MENTOR":NEELA SANTOSH


Description --

My Chrome Extension project is designed to help users track their productivity and visualize how they spend their time online. The main idea behind the extension is simple: whenever a user visits a website, the extension records the time spent and stores it as a log. Later, when the user opens the popup, they can see a list of sites along with the duration of time spent on each. To make this data more meaningful, I integrated Chart.js so that the logs are not only displayed as text but also represented visually in the form of a pie chart. This gives users a clear picture of how their time is distributed across different activities.

The extension is built using standard web technologies like HTML, CSS, and JavaScript. The manifest.json file defines the extension’s metadata and permissions, while background scripts handle the continuous tracking of time even when the popup is closed. The popup itself is a simple HTML page styled with CSS, and it loads a JavaScript file that fetches logs from chrome.storage.local. Each log contains the URL and the duration, which are then displayed as list items. This makes it easy for users to quickly glance at their browsing history and see how long they spent on each site.

The most engaging part of the extension is the pie chart visualization. Using Chart.js, I take the stored logs and convert them into labels and data points. Each slice of the pie chart represents a website, and the size of the slice corresponds to the time spent there. For example, if a user spends 40% of their time on coding sites, 30% on social media, and 30% on research, the chart immediately shows this distribution in a colorful, easy‑to‑understand format. This visual feedback helps users identify patterns in their browsing behavior and make adjustments to improve productivity.

Overall, the extension works by combining background tracking, local storage, and a popup interface with chart visualization. It is lightweight, easy to use, and provides both raw data and visual insights. By showing users exactly where their time goes, the extension encourages better focus and time management. I see it as a practical tool for anyone who wants to be more mindful of their online habits and take control of their productivity.


Output--
<img width="1912" height="879" alt="Image" src="https://github.com/user-attachments/assets/6c04234d-b229-4f32-8e36-05a557d60c78" />

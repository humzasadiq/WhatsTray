<p align="center"><img src="https://github.com/humzasadiq/WhatsTray/blob/main/assets/tray-icon_bundle.png" alt="WT Logo" width="100"></p>
<h1 align="center">WhatsTray</h1>  
<p align="center">A Whatsapp web tray client for Windows <br> Built with <code>Electron.js</code>  </p>  
<hr>
 
<p><img src="https://github.com/humzasadiq/WhatsTray/blob/main/assets/lv_0_20240506003305-ezgif.com-video-to-gif-converter.gif?raw=true" alt="gif"></p>  
<h2>Installation:</h2>
<p> 
<ul>
 <li>Download latest release <a href="https://github.com/humzasadiq/WhatsTray/releases/latest" target="_blank">here</a></li> 
 <li>Run the installer</li>
</ul>
</p>
<h2>Whatsapp Data</h2>
<p>
In WhatsTray, your WhatsApp data is stored within the Electron app's own environment locally on your computer, rather than within the Windows Edge browser or any other installed browsers on your PC. Here's how it works:

When you launch WhatsTray, it creates an instance of the Edge browser within the Electron app itself. This instance of Edge is isolated from any other browsers you may have installed on your system. It operates independently, meaning it doesn't interact with your system's main Edge browser or any other browser profiles you might have.

Now, where does your WhatsApp data reside within this Electron app environment? WhatsTray allocates a dedicated space for your WhatsApp data within its own internal storage structure. Specifically, your WhatsApp data, including messages, settings, and other related information, is stored in a location within the Electron app's directory structure. Typically, this storage location is within the app's data directory, often found in a designated folder like \Users\User\AppData\Roaming\whatsapp-tray\Local Storage.</p>

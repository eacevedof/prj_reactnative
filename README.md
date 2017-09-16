# prj_reactnative
prj_reactnative  (windows)

<url>https://facebook.github.io/react-native/docs/getting-started.html</url>
<url>https://shift.infinite.red/getting-started-with-react-native-development-for-windows-ba23a4be90b6</url>


<ol>
    <li>npm install -g create-react-native-app</li>
    <li>Esto da un error. Hay que configurar el proxy npm config set proxy http://youproxy:80</li>
    <li>
        <b>Error:</b>
        <p>
        npm WARN enoent ENOENT: no such file or directory, open 'C:\xampp\htdocs\prj_reactnative\package.json'
        npm WARN rnpm-plugin-windows@0.2.6 requires a peer of react-native@>=0.31.0 but none was installed.
        npm WARN prj_reactnative No description
        npm WARN prj_reactnative No repository field.
        npm WARN prj_reactnative No README data
        npm WARN prj_reactnative No license field.
        </p>
        <b>Sol:</b>
        <p>
        https://github.com/visionmedia/debug/issues/261
        </p>
        <p>
        $ react-native windows
        Scanning 759 folders for symlinks in C:\xampp\htdocs\prj_reactnative\AwesomeProject\node_modules (45ms)
        Reading application name from package.json...
        Reading react-native version from node_modules...
        Checking for react-native-windows version matching 0.45.*...
        Could not find react-native-windows@0.45.*.
        </p>
        <b>Sol:</b>
        <p>
        
        </p>
    </li>
</ol>
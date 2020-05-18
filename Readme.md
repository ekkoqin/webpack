This is a project followed https://segmentfault.com/a/1190000006178770  
This project based on the newest webpack version webpack 4x   
I have added babel loader, css loader, style loader, postcss loader in to the webpack.config.js //setting area  
I have installed and implement several plugins such as HtmlWebpackPlugin(create new index.html in the build dir based on html template), HotModuleReplacementPlugin(hot update), MiniCssExtractPlugin(minimize css), 
CleanWebpackPlugin(clean bundle.js versions), BannerPlugin(copyright) and so on into both the webpack.config.js and webpack.production.config.js.// plugin area    

//loader function: analyze code, compile code, run code.

//plugin function: help us optimize the project structure, make the dev process easier, optimize the final size of the project, optimization(will not go to compile code).

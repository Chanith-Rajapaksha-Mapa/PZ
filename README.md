# PZ
Best of the Priety Zinta's Movies
body {
    font-family: Century Gothic, sans-serif;
    font-size: 14px;
    color: #9ab;
    background: #101010;
    margin: 0;
}

.container {
    margin: 20px auto;
    width: 1000px;
    padding: 12px;
    border-radius: 10px;
    background: #14181c;
    background: #202020;
}

.title { 
    font-family: Tahoma, Geneva, sans-serif;
    font-size: 28px; 
    font-weight: bold; 
    color: white; 
    display: flex;
    align-items: center;
    justify-content: space-between;
}

.title .link-buttons {
    display: flex;
    align-items: center;
    font-size: 14px;
}

.title .link-buttons.grayscale .link-button {
    filter: grayscale(70%);
}

.title .link-buttons.grayscale .link-button:hover {
    filter: unset;
}

.title .link-buttons .link-button,
.title .link-buttons a {
    margin-left: 8px;
}

.sub-title {
    margin-top: 8px;
}

.sub-title span {
    margin-right: 20px;
}

.year {
    margin-left: 16px;
}

.header-buttons {
    margin-top: 16px;
}

.bar {
    border-top: 1px solid rgb(153, 170, 187);
    margin: 0 0 12px;
    position: relative;
}

.years-list, .genres-list {
    margin-top: 16px;
}

.phone-home,
.phone-home:visited,
.phone-home:link,
.phone-home:active {
    font-size: 12px;
    color: #9ab;
    text-decoration: none;
    position: absolute;
    right: 0;
    top: -18px;
}

.phone-home:hover {
    color: #40bcf4;
}

.header-green {
    font-family: Georgia, Serif;
    font-size: 22px;
    color: rgb(0, 224, 84);
    font-weight: bold;
    padding: 8px 0;
}

a.button-darkgray, a.button-darkgray:visited, a.button-darkgray:link {
    color: #9ab;
    background: #283038;
    text-decoration: none;
    display: inline-block;
    padding: 5px 8px;
    font-size: 14px;
    white-space: nowrap;
    border-radius: 3px;
    box-shadow: inset 0 1px 0 hsl(0deg 0% 100% / 5%);
    margin-right: 4px;
    margin-bottom: 4px;   
}

a.button-darkgray:hover {
    color: #def;
    background: #303840;
}

.upper {
    text-transform: uppercase;
}

.navigation-bar {
    margin-bottom: 12px;
    display: flex;
    align-items: center;
    justify-content: space-between;
}

.navigation-bar .left {
    display: flex;
    align-items: center;
}

.navigation-bar .left .arrow {
    margin: 0 8px;
}

.link-gray a:link    {  color: #9ab; text-decoration: none; }
.link-gray a:visited {  color: #9ab; text-decoration: none; }
.link-gray a:active  {  color: #9ab; text-decoration: none; }
.link-gray a:hover   {  color: #40bcf4; text-decoration: none; }

b {
    color: #abc;
    font-weight: bold;
    margin-right: 10px;
}

.tagline {
    margin: 12px 0 16px;
    font-size: 16px;
    min-height: 8px;
    font-style: italic;
}

.actor-paragraph {
    display: flex;
    align-items: center;
    margin-right: 100px;
    margin-bottom: 8px;
}

.actor-image-container {
    flex: 0 0 90px;
    display: inline-block;
}

.actor-image {
    border-radius: 4px;
}

.shiny-container {
    position: relative;
    display: inline-block;
}

.shiny-frame {
    display: block;
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 3px;
    overflow: hidden;
    box-sizing: border-box;
    box-shadow: inset 0 0 0 1px rgb(221 238 255 / 35%);
    background-image: linear-gradient(90deg,hsla(0,0%,100%,0) 0,hsla(0,0%,100%,.5) 50%,hsla(0,0%,100%,0));
    background-repeat: no-repeat;
    background-clip: padding-box;
    background-size: 100% 1px;
    border-radius: 4px;
}

.shiny-frame.large {
    border-radius: 6px;
}

.actor-name {
    flex: 0 0 calc(50% - 90px);
}

.character-name {
    flex: 1 1 auto;
    display: flex;
    justify-content: flex-end;
}

.footer {
    margin-top: 80px;
    border-top: 2px solid #101010;
    padding: 20px;
    text-align: center;
    font-size: 12px; 
    margin-left: -12px;
    width: calc(100% + 24px);
}

.movie-container {
    display: flex;
    align-items: flex-start;
    margin-top: 12px;
}

.movie-container .left {
}

.movie-container .right {
    margin-left: 24px;
}

.poster { 
    border-radius: 6px;
}

.stars-row {
    display: flex;
    align-items: center;
    margin-top: 8px;
}

.stars-row .description {
    width: 150px;
}

.stars-row .stars {
    width: 200px;
    display: inline-flex;
    justify-content: center;
}

.stars-row .stars img {
    width: 20px;
    margin: 4px 0 0 -2px;
}

.stars-row .votes {
    //margin-left: 8px;
}


ul.movie-list {
    list-style-type: none;
    padding-left: 16px;
}

ul.movie-list > li {
    margin-bottom: 3px;
}

ul.movie-list > li.thumbnail {
    display: inline-block;
    width: 240px;
    max-width: 240px;
    overflow: hidden;
    text-align: center;
    margin: 8px 0;
    vertical-align: top;
}

.thumbnail .shiny-container {
    display: inline-block;
}

.thumbnail .shiny-container img {
    border-radius: 4px;
}

ul.movie-list > li.thumbnail .thumbnail-text {
    margin: 8px 0 8px;
}

.player {
    width: 100%;
    margin: 16px 0;
    border-radius: 4px;
}

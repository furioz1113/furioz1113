- 👋 Hi, I’m @furioz1113
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
furioz1113/furioz1113 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->


:root{
    --title-gradient:linear-gradient(to right,#37b1da ,#c948cd ,#cce335, #37b1da);
    --primary-color:#75a00d;
    --background-secondary: #0a0a0a;
    --outline-color:#0a0a0a;
    --outline-lightcolor:#303030;
    --app-color:#0b0b0b;
    --channels-color:#111;
    --channeltextarea-background: #000;
    --channels-darker:#0c0c0c;
    --channels-selected:#191919;
    --channels-text-selected:#9fca2b;
    --chat-color:#0b0b0b;
    --mention-color:#1f1f1f;
    --scrollbar-bg:#202020;
    --scrollbar-thumb:#414141;
    --text-input:#191919;
    --dropdown-color:#232323;
    --link-color:#96c83c;
    --channel-radius:5px;
    --text-color:#cbcbcb;
    --text-darker:#b0b0b0;
    --font:'Verdana',Helvetica,Arial,sans-serif;
    --important-notification-l:#f84747;
    --important-notification:#d12020;
    
}
/**
* @name xyhlo snippets
* @author lolpowerluke 
* @version 1.0.0
* @description snippets for xhylo, thanks lolpowerluke for helping me make this
*/
:root {
  --avatar-shape: 50%;  /* 50% for round - 0% for square */
  --online: #1df594;  /* Colour for online status */
  --idle: #faa61a;  /* Colour for idle status */
  --dnd: #f04747;  /* Colour for dnd status */
  --offline: #4d4d4d;  /* Colour for offline status */
  --streaming: #643da7;  /* Colour for streaming status */
  --invisible: #747f8d;  /* Colour for invisible status - Note: this will only show for your own invisibility */
}

.peopleListItem-u6dGxF,
.userInfo-2WpsYG,
.wrapper-1VLyxH > svg {
  overflow: visible;
}
.avatar-6qzftW {
  margin-left: 5px;
}
.wrapper-1VLyxH > svg > foreignObject {
  mask: none;
  border-radius: var(--avatar-shape);
}
:not(.UserDetails-mutualFriends-mutualFriend) > .wrapper-1VLyxH > svg > rect {
  mask: none;
  rx: 5;
  y: 6;
  x: -10;
  height: 20px;
  width: 2px;
}
.message-2CShn3 .wrapper-1VLyxH > svg > rect {
  y: 6;
  height: 25px;
}
.userPopout-2j1gM4 :not(.UserDetails-mutualFriends-mutualFriend) > .wrapper-1VLyxH > svg > rect {
  y: 13;
  height: 50px;
}
.focusLock-2tveLW .header-S26rhB .wrapper-1VLyxH > svg > rect {
  y: 14;
  height: 90px;
}
.focusLock-2tveLW .body-1Ukv50 .wrapper-1VLyxH > svg > rect {
  height: 25px;
  y: 7;
}
.container-YkUktl .wrapper-1VLyxH > svg > rect {
  x: -5;
}


[data-status="streaming"] > .StatusEverywhere-avatar-chatAvatar > svg.mask-1FEkla.svg-2azL_l,
.wrapper-1VLyxH[aria-label*="Streaming"]>svg.mask-1FEkla.svg-2azL_l {
  filter: drop-shadow(0 0 5px var(--streaming));
}
[data-status="offline"] > .StatusEverywhere-avatar-chatAvatar > svg.mask-1FEkla.svg-2azL_l,
.wrapper-1VLyxH[aria-label*="Offline"]>svg.mask-1FEkla.svg-2azL_l {
  filter: drop-shadow(0 0 7px var(--offline));
}
[data-status="dnd"] > .StatusEverywhere-avatar-chatAvatar > svg.mask-1FEkla.svg-2azL_l,
.wrapper-1VLyxH[aria-label*="Do Not Disturb"]>svg.mask-1FEkla.svg-2azL_l {
  filter: drop-shadow(0 0 5px var(--dnd));
}
[data-status="idle"] > .StatusEverywhere-avatar-chatAvatar > svg.mask-1FEkla.svg-2azL_l,
.wrapper-1VLyxH[aria-label*="Idle"]>svg.mask-1FEkla.svg-2azL_l {
  filter: drop-shadow(0 0 5px var(--idle));
}
[data-status="online"] > .StatusEverywhere-avatar-chatAvatar > svg.mask-1FEkla.svg-2azL_l,
.wrapper-1VLyxH[aria-label*="Online"]>svg.mask-1FEkla.svg-2azL_l {
  filter: drop-shadow(0 0 5px var(--online));
}
[data-status="online"] .wrapper-1VLyxH rect[fill*="#"],
[aria-label*="Online"] .mask-1FEkla > foreignObject + rect,
[aria-label*="Online"] .mask-2Me5HY > foreignObject + rect,
[aria-label*="Online"] .mask-1FEkla > svg > rect,
[aria-label*="Online"] .mask-2Me5HY > svg > rect {
fill: var(--online);
}
[data-status="idle"] .wrapper-1VLyxH rect[fill*="#"],
[aria-label*="Idle"] .mask-1FEkla > foreignObject + rect,
[aria-label*="Idle"] .mask-2Me5HY > foreignObject + rect,
[aria-label*="Idle"] .mask-1FEkla > svg > rect,
[aria-label*="Idle"] .mask-2Me5HY > svg > rect {
  fill: var(--idle);
}
[data-status="dnd"] .wrapper-1VLyxH rect[fill*="#"],
[aria-label*="Do Not Disturb"] .mask-1FEkla > foreignObject + rect,
[aria-label*="Do Not Disturb"] .mask-2Me5HY > foreignObject + rect,
[aria-label*="Do Not Disturb"] .mask-1FEkla > svg > rect,
[aria-label*="Do Not Disturb"] .mask-2Me5HY > svg > rect {
  fill: var(--dnd);
}
[data-status="offline"] .wrapper-1VLyxH rect[fill*="#"],
[aria-label*="Offline"] .mask-1FEkla > foreignObject + rect,
[aria-label*="Offline"] .mask-2Me5HY > foreignObject + rect,
[aria-label*="Offline"] .mask-1FEkla > svg > rect,
[aria-label*="Offline"] .mask-2Me5HY > svg > rect {
  fill: var(--offline);
}
[data-status="invisible"] .wrapper-1VLyxH rect[fill*="#"],
[aria-label*="Invisible"] .mask-1FEkla > foreignObject + rect,
[aria-label*="Invisible"] .mask-2Me5HY > foreignObject + rect,
[aria-label*="Invisible"] .mask-1FEkla > svg > rect,
[aria-label*="Invisible"] .mask-2Me5HY > svg > rect {
  fill: var(--offline);
}
[data-status="streaming"] .wrapper-1VLyxH rect[fill*="#"],
[aria-label*="Streaming"] .mask-1FEkla > foreignObject + rect,
[aria-label*="Streaming"] .mask-2Me5HY > foreignObject + rect,
[aria-label*="Streaming"] .mask-1FEkla > svg > rect,
[aria-label*="Streaming"] .mask-2Me5HY > svg > rect {
  fill: var(--streaming);
}


.search-2oPWTC:not(.open-6_Y_aH) .searchBar-3dMhjb { width: 27px; transition: 0.25s; background-color: transparent;}
.search-2oPWTC:not(.open-6_Y_aH):hover .searchBar-3dMhjb { width: 240px; background-color: var(--background-tertiary);}
.search-2oPWTC:not(.open-6_Y_aH) .iconContainer-O4O2CN { transform: scale(1.3); transition: 0.25s;}
.search-2oPWTC:not(.open-6_Y_aH):hover .iconContainer-O4O2CN { transform: scale(1);}
.icon-3cZ1F_ { color: var(--text-normal)}



.scrollableContainer-2NUZem { padding-right: 11px ; }

.typeWindows-1za-n7 {
    animation: rgbTop 3s infinite linear;
}
@keyframes rgbTop {
    0% {
        background-position: 1920px;
    }
    100% {
        background-position: 0px;
    }
}

.scrollableContainer-2NUZem::-webkit-scrollbar {
    display: none;
}

[aria-label="Inbox"],
[href="https://support.discord.com"] {
  display: none;
}
.avatarHintInner-1TvA8u {
    font-size: 8px !important;
}

/* Change ping badge color */
.numberBadge-2s8kKX {background-color: #6e9601 !important}

/*Remove Stage Discovery Tab*/
#private-channels [href="/discovery"] {display: none}

/*Remove Library Tab*/
#private-channels [href="/library"] {display: none}

/*Remove Nitro Tab*/
#private-channels [href="/store"] {display: none}

/*Unread channels rainbow wave*/
.wrapper-2jXpOf.modeUnread-1qO3K1 .name-23GUGE {
    background-image: linear-gradient(to left,rgb(51, 255, 0), rgb(255, 230, 0), red, rgb(234, 0, 255), rgb(0, 140, 255), rgb(51, 255, 0));
    animation: gradient-border 3s linear infinite;
    background-size: 400% 100%;
    color: transparent !important;
    -webkit-background-clip: text;
    position: relative;
    z-index: 1;
}
@keyframes gradient-border {
    0%, 200% {
        background-position: 0 0;
    }

    99.999999999999999% {
        background-position: 130% 0;
    }
}
/*Remove gift nitro and stickers button*/
.button-38aScr[aria-label="Send a gift"] {
    display:none;
    }
    .button-38aScr[aria-label="Open sticker picker"] {
    display:none;
    }
    
.expandedFolderBackground-1cujaW,.expandedFolderIconWrapper-Huv7r{/*couleur fichier ouvert*/
    background-color:#0a0a0a!important;
}
.members-1998pB, 
.members-1998pB > .content-3YMskv {
    background: #0a0a0a !important;
}
#app-mount .wrapper-1Rf91z {
    background-color: #0a0a0a !important;
}
/*Change selected channel side color*/
.containerDefault--pIXnN.selected-3LIHYU {
    border-left: 6px solid #9fca2b;
}

#app-mount .container-3auIfb, #app-mount .bd-switch-body {
    width: 20px;
    height: 20px;
    background: transparent !important;
  }
  #app-mount .container-3auIfb .slider-TkfMQL, #app-mount .bd-switch-body .bd-switch-slider {
    left: -6px !important;
  }
  #app-mount .container-3auIfb .slider-TkfMQL > rect, #app-mount .bd-switch-body .bd-switch-slider rect {
    height: 20px !important;
    width: 20px !important;
    x: 4px !important;
    y: 0px !important;
    rx: 5;
    fill: var(--background-tertiary);
  }

.wrapper-3NnKdC::before { /*Guild wrapper background*/
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    bottom: 0;
    right: 0;
    background: #0a0a0a;
    background-size: cover;
}
.tree-2wKJdG, .scroller-1Bvpku,.wrapper-3NnKdC { /*Guild subcontainer*/
    background: transparent;
}
/*connections look cooler*/
.connectedAccount-2Jb-Z0:active{
    border-width: 1.2px 1.2px 1.2px 1.2px;
    transform: translateY(1px);
    transition: 0.1s;
}
.connectedAccount-2Jb-Z0
{
    border: solid #151b27;
    border-width: 1.2px 1.2px 3px 1.2px;
    border-radius: 4px;
    transition: 0.1s;
}

.scrollableContainer-2NUZem {
    border: 1px solid #9fca2b;
  }
  svg.homeIcon-FuNwkv{
    color:transparent;
}

/* Custom home icon */
#app-mount .listItemWrapper-KhRmzM .childWrapper-anI2G9 {
    background: url('https://i.ytimg.com/vi/meqVOjIO45A/maxresdefault.jpg') center/cover no-repeat;
}
.homeIcon-FuNwkv {
    display: none;
}
*{
    font-size: 15px!important;
    font-family:var(--font)!important
}

strong{
    font-weight:normal
}

a{
    color:var(--link-color)
}

body{

    font-family:var(--font)!important;
    background-color:var(--app-color)
    
}

input,textarea{
    font-family:var(--font)!important
}

.wrapper-1Rf91z{
	background-color:#191919;
}

.appMount-3lHmkl{
    left:6px;
    top:6px;
    height:calc(100vh - 12px);
    width:calc(100vw - 12px);
    box-shadow:0 0 0 1px #3c3c3c,0 0 0 4px #282828,0 0 0 5px #3c3c3c,0 0 0 6px #0a0a0a;
    background-color:var(--channels-color)
}

.typeWindows-1za-n7{
    height:25px;
    background:var(--primary-color);
    margin-top:1px!important;
    margin-left:1px;
    margin-right:1px;
    background:var(--title-gradient);
    box-shadow:inset 0 -23px 0 0 var(--app-color),inset 0 -24px 0 0 rgba(0,0,0,0.5);
    opacity:1.0;
    z-index:50;
    border-bottom:1px solid var(--outline-lightcolor)
}

*/.typeWindows-1za-n7:hover{
	height:20px;
	transition: all .6s;
	opacity: 1;
}*/

.winButton-iRh8-Z{
    top:2px!important
}
.wordmark-2iDDfm{
    opacity:1.0;
    font-family:'Raleway'
}
.wordmark-2iDDfm::before{
    content:'game';
    font-size:14px;
    z-index:1000;
    position:fixed;
    display:inline-block;
    color:var(--text-color);
    height:auto;
    top:12px;
    left:12px;
    background-color:transparent
}
.mention-1f5kbO {
    background-color: var(--primary-color)!important;
}
.wordmark-2iDDfm::after{
    content:'sense';
    font-size:14px;
    z-index:1000;
    position:fixed;
    display:inline-block;
    color:var(--primary-color);
    height:auto;
    top:12px;
    left:52px;
    background-color:transparent
}

.winButtonClose-1HsbF-{
    height:33px;
}
.winButtonClose-1HsbF-:hover{
    background-color: transparent;
}
.winButtonMinMax-PBQ2gm{
	height:33px;
}
.winButtonMinMax-PBQ2gm:hover{
    background-color: transparent;
}
.wordmark-2iDDfm svg{
    display:none
}
.theme-dark .guildsWrapper{
    background:var(--channels-darker);
    box-shadow:inset -1px 0 0 0 #303030,inset -2px 0 0 0 #000
}
.guildsWrapper .guildsAdd-21_Id{
    border-radius:0;
    background:var(--chat-color);
    border:1px dashed var(--outline-lightcolor);
    color:var(--outline-lightcolor)
}
.guildsWrapper-1Rf91z .guildsAdd-21_Id:hover{
    color:var(--text-color);
    border-color:var(--text-color)
}
.guildsWrapper-1Rf91z .guildsAdd-21_Id-inner{
    top:-2px
}
.guildsWrapper-1Rf91z .guilds-1q_RqH .guilds-1q_RqH+.guilds-1q_RqH{
    margin-bottom:25px;
    margin-top:25px
}
.guildInner-3DSoA4{
    border-radius:0!important
}
.guildsWrapper-1Rf91z .guilds-1q_RqH .guild-1EfMGQ+.guild-1EfMGQ{
    margin-top:25px
}
.guildsWrapper-1Rf91z .guilds-1q_RqH .friendsOnline-_wi_fM{
    padding-bottom:10px;
    font-size:9px
}
.guildsWrapper-1Rf91z .guilds-1q_RqH .guild-1EfMGQ.selected-ML3OIq:before{
    box-shadow:0 1px 0 0 #303030,-1px 2px 0 0 #000,0 -1px 0 0 #303030,-1px -2px 0 0 #000;
    background:var(--channels-color);
    border-radius:0;
    height:70px;
    margin-top:-35px;
    width:75px;
    -webkit-transition:none;
    transition:none
}
.guildsWrapper-1Rf91z .guilds-1q_RqH .guild-1EfMGQ .guildInner-3DSoA4{
    background:var(--chat-color)!important
}
.guildsWrapper-1Rf91z .guilds-1q_RqH .guild-1EfMGQ.selected-ML3OIq .guildInner-3DSoA4 a{
    background-color:var(--primary-color)!important;
    transition:all .3s ease
}
.guildsWrapper-1Rf91z .guilds-1q_RqH .guild-1EfMGQ.selected-ML3OIq .guildInner-3DSoA4{
    background-color:var(--primary-color)!important;
    transition:all .3s ease
}
.guildInner-3DSoA4{
    background-color:var(--primary-color);
    border-radius:var(--channel-radius)!important;
    transition:all .3s ease
}
.guildInner-3DSoA4:hover{
    background-color:var(--primary-color)!important;
    transition:all .3s ease
}
.guild-1EfMGQ.active .guildInner-3DSoA4{
    background:var(--primary-color)!important
}
.guildsWrapper-1Rf91z .guildseparator-1X4GQ1{
    display:none
}
.guildsAdd-21_IdK {
	border-radius: 10%;
}
.avatar-large,.avatar-profile,.avatar-small,.avatar-xlarge,.avatar-xsmall,.avatar-xxlarge{
    border-radius:var(--channel-radius)!important
}
.avatarHint-1qgaV3{
	border-radius:var(--channel-radius)!important
}
.container-PNkimc{
    background:none!important
}
.base-3dtUhz{
    border-radius:0!important
}
.header-2o-2hj{
    background:var(--channels-darker);
    box-shadow:none!important;
    border-bottom:1px solid var(--outline-lightcolor)
}
.header-2o-2hj:hover{
    background:var(--channels-selected)
}
.container-1UB9sr{
    border-top:1px solid var(--outline-lightcolor);
    border-bottom:0;
    background:var(--chat-color);
    font-size:11px;
    padding:5px 10px 5px 10px
}
.channels-Ie2l6A.vertical-V37hAW.flex-1O1GKY.directionColumn-35P_nr {
    background:var(--channels-color);
    border-right:1px solid var(--outline-lightcolor)
}
.name-3M0b8v{
    font-size:13px;
    font-weight:700
}
.contentSelectedText-3wUhMi{
    background:var(--channels-selected)
}

.nameSelectedText-sp_EUw,.nameSelectedVoice-1qSph5,svg.colorSelectedText-1y4Wvs.icon-sxakjD,svg.colorSelectedVoice-Xcb_9R.icon-sxakjD{
    color:var(--channels-text-selected)!important;
    opacity:1
}


.theme-dark .member-3W1lQa:hover .content-OzHfo4, .theme-dark .member-3W1lQa.popout-open .content-OzHfo4, .theme-dark .member-3W1lQa.popout-open:hover .content-OzHfo4 {
	background:var(--channels-selected)
}

.contentHoveredText-2D9B-x,.contentHoveredVoice-3p_NEO,.contentHoveredVoice-3p_NEO:active,.contentSelectedVoice-1WDIBM:active{
    background:none!important
}
.container-2Thooq{
    background:var(--channels-darker);
    border-top:1px solid var(--outline-lightcolor)
}
.popout{
    background:var(--dropdown-color)!important;
    border:solid 1px var(--outline-color)!important;
    border-radius:1px
}
.small-popout-box{
    background:var(--dropdown-color)!important;
    border:solid 1px var(--outline-color)!important;
    border-radius:1px
}

.theme-dark .messagesPopoutWrap-1MQ1bW .footer-1kmXd4 {
    background: var(--channels-darker)!important;
}
.theme-dark .messagesPopoutWrap-1MQ1bW {
    border-radius: 1px;
    background: var(--channels-color)!important;
    box-shadow: 0 0 0 1px #323232,0 0 0 2px #0a0a0a!important;
}

.theme-dark .messagesPopoutWrap-1MQ1bW .header-ykumBX {
    -webkit-box-shadow: 0 2px 3px 0 rgba(0,0,0,20%);
    background-color: #35393e;
    box-shadow: 0 2px 3px 0 rgba(0,0,0,.2);
    background: var(--channels-darker)!important;
}

.option-popout .btn-item,.option-popout .btn-item:hover{
    color:var(--text-color)
}
.contextMenu-HLZMGh{
    background:var(--dropdown-color)!important;
    border:solid 1px var(--outline-color)!important;
    border-radius:1px;
    box-shadow:none!important
}
.item-1Yvehc{
    font-size:11px!important
}
.item-1Yvehc:hover{
    background:var(--outline-lightcolor)!important;
    border-radius:0
}
.itemSubMenu-1vN_Yn{
    background-color:var(--dropdown-color)!important
}
.menu-Sp6bN1{
    border-radius:1px;
	background:var(--chat-color)!important;
	box-shadow:0 0 0 1px #323232,0 0 0 2px #0a0a0a!important;
}
.item-1GzJrl{
    color:var(--text-color);
    font-size:11px!important
}
.item-1GzJrl:hover{
    border-radius:0!important;
    color:var(--text-color);
    background:var(--outline-lightcolor)!important
}
.separator-2zcjq8{
    border-color:var(--outline-lightcolor)!important;
    width:100%
}
.title-3qD0b-,.titleCall-_b9o8P{
    background:var(--channels-darker)!important;
    box-shadow:inset 0 -1px 0 var(--outline-lightcolor)!important
}
.channelName-3stJzi{
    font-size:13px;
    color:var(--text-color)!important
}
.channelName-3stJzi svg{
    width:14px;
    color:var(--text-color)
}
.channelIcon-MsmKOO{
    top:4px
}
.topic-2QX7LI{
    font-size:11px
}
.messagesWrapper-3lZDfY {
    background:none!important
}
.chat-3bRxxu>.content-yTz4x3{
    background:var(--chat-color)!important
}
.embedPill-1Zntps{
    background:var(--primary-color)!important
}
.embedInner-1-fpTo{
    background:var(--channels-darker)!important;
    border-radius:1px!important;
    border-color:var(--outline-lightcolor)!important
}
.message-group{
    padding:15px 0
}
.message-group h2 strong{
    font-size:13px
}
.timestampCozy-2hLAPV{
    font-size:9px
}
.markup-2BOw-j{
    font-size:11px;
    line-height:1.4em
}
.markup-2BOw-j pre{
    border-radius:1px!important;
    border:none!important;
    box-shadow:0 0 0 1px #323232,0 0 0 2px #101010!important
}
.markup-2BOw-j pre code{
    font-size:13px;
    background:var(--dropdown-color)!important
}
.hljs-section{
    color:var(--primary-color)!important
}

.theme-dark .divider-3gKybi.dividerRed-MKoLlr .dividerContent-2L12VI>span {
    background:#113!important
}

.theme-dark .divider-3gKybi.dividerRed-MKoLlr .dividerContent-2L12VI:after, .theme-dark .divider-3gKybi.dividerRed-MKoLlr .dividerContent-2L12VI:before {
background:var(--important-notification)!important;
border-color: transparent !important;

}

.theme-dark .divider-3gKybi span {
	background:0b0b0b!important
}
.imageWrapper-2p5ogY{
    border-radius:3px
}
.chat-3bRxxu form{
    background:none!important;
    box-shadow:none!important
}
.inner-zqa7da{
    border-radius:0!important;
    background:var(--text-input)!important;
    box-shadow:inset 0 0 0 1px #323232,inset 0 0 0 2px #101010
}

.channelTextArea-rNsIhG .inner-zqa7da .textArea-2Spzkt{
    font-size:11px;
    line-height: 1.6rem;
}

.theme-dark .channelTextArea-rNsIhG {
	border-top:none;
}
.innerEnabled-3g80kR .textArea-2Spzkt{
    font-size:11px;
    line-height:.80rem;
    margin:12px 2px 2px 0;
    padding:5px 38px 8px 10px
}
.textAreaEnabled-3vQ5WZ{
    padding:5px 38px 8px 0
}
.typing-2GQL18{
    background:none!important;
    font-size:8px!important;
    padding-left:1px
}
.typing-2GQL18 .ellipsis-19qdx6{
    display:none
}
.scroller-2FKFPG.members-1998pB{
    background:var(--channels-darker)!important;
    border-left:solid 1px var(--outline-lightcolor);
    color:red
}

.image-33JSyf{
	border-radius:var(--channel-radius)!important
}

.mask-3OgeRz{
	-webkit-mask: none;
}
::-webkit-scrollbar-thumb{
    border:none!important;
    border-radius:0!important;
    background:#414141!important
}
::-webkit-scrollbar{
    width:6px!important
}
::-webkit-scrollbar-track-piece{
    border:none!important;
    border-radius:0!important;
    background:#2d2d2d!important
}
.scroller-wrap .scroller::-webkit-scrollbar-thumb{
    border:none!important;
    border-radius:0!important;
    background:#414141!important
}
.scroller-wrap .scroller::-webkit-scrollbar{
    width:6px!important
}
.scrollerWrap-2lJEkd .scroller::-webkit-scrollbar-track-piece{
    border:none!important;
    border-radius:0!important;
    background:#2d2d2d!important
}
.scrollerWrap-2lJEkd.scroller::-webkit-scrollbar-thumb{
    border:none!important;
    border-radius:0!important;
    background:#414141!important
}
.scrollerWrap-2lJEkd .scroller::-webkit-scrollbar{
    width:6px!important
}
.scrollerWrap-2lJEkd .scroller::-webkit-scrollbar-track-piece{
    border:none!important;
    border-radius:0!important;
    background:#2d2d2d!important
}
.tooltip,.tooltip.tooltip-black,.tipsy-inner{
    border-radius:1px!important
}
.bd-blue .tooltip-red,.tooltip.tooltip-red{
    background-color:var(--important-notification)
}
.bd-blue .tooltip-red.tooltip-top:after{
    border-top-color:var(--important-notification)
}
.bd-blue .tooltip-red.tooltip-left:after{
    border-left-color:var(--important-notification)
}
.bd-blue .tooltip-red.tooltip-bottom:after{
    border-bottom-color:var(--important-notification)
}
.bd-blue .tooltip-red.tooltip-right:after,.tooltip.tooltip-red.tooltip-right:after{
    border-right-color:var(--important-notification)
}
.tooltip.tooltip-right:after,.tooltip.tooltip-left:after{
    margin-top:-8px
}
.tooltip.tooltip-brand,.tooltip.tooltip-black,.tipsy-inner{
    background:var(--channels-darker)!important;
    border:solid 1px var(--outline-lightcolor)!important;
    border-radius:1px;
    padding:5px 10px;
    font-size:11px;
    font-weight:400;
    line-height:14px;
    text-align:center
}
.tooltip.tooltip-brand.tooltip-right:after,.tooltip.tooltip-black.tooltip-right:after{
    border-radius:0;
    border-right:8px solid var(--outline-lightcolor)!important;
    border-top:8px solid transparent!important;
    border-bottom:8px solid transparent!important
}
.tooltip.tooltip-brand.tooltip-top:after,.tooltip.tooltip-black.tooltip-top:after,.tipsy-se .tipsy-inner:after{
    border-radius:0;
    border-right:8px solid transparent!important;
    border-top:8px solid var(--outline-lightcolor)!important;
    border-left:8px solid transparent!important
}
.tooltip.tooltip-brand.tooltip-left:after,.tooltip.tooltip-black.tooltip-left:after{
    border-radius:0;
    border-left:8px solid var(--outline-lightcolor)!important;
    border-top:8px solid transparent!important;
    border-bottom:8px solid transparent!important
}
.tooltip.tooltip-brand.tooltip-bottom:after,.tooltip.tooltip-black.tooltip-bottom:after{
    border-radius:0;
    border-right:8px solid transparent!important;
    border-bottom:8px solid var(--outline-lightcolor)!important;
    border-left:8px solid transparent!important
}
.checkbox{
    width:8px;
    height:8px;
    background:#4c4c4c;
    background:linear-gradient(to bottom,#4c4c4c 0,#333 100%);
    border-radius:0!important;
    border:1px solid var(--outline-color)
}
.checkbox .checkbox-inner{
    height:8px;
    width:8px;
    border:0
}
.checkbox .checkbox-inner span{
    border:0;
    border-radius:0;
    background:linear-gradient(to bottom,#4c4c4c 0,#333 100%)
}
.checkbox .checkbox-inner input[type=checkbox]:checked+span{
    background:linear-gradient(to bottom,#9cc728 0,#7aa506 100%);
    transition:5.0
}
.checkbox .checkbox-inner input[type=checkbox]:checked+span:after{
    content:none
}
.checkbox .checkbox-inner+span{
    white-space:nowrap;
    color:var(--text-color);
    font-size:11px
}
.grabber-3mFHz2{
    border-radius:5px!important;
    margin-left:-6px!important
}
.bar-2Qqk5Z{
    background:linear-gradient(to bottom,#343434 0,#444 100%)!important;
    border-radius:0!important;
    border:1px solid var(--outline-color)
}
.barFill-23-gu-{
    background:linear-gradient(to bottom,#99c427 0,#699404 100%)!important
}
.bubble-3we2di{
    background:var(--channels-darker)!important;
    border:solid 1px var(--outline-lightcolor)!important;
    border-radius:1px;
    font-size:10px;
    color:var(--text-color)
}
.bubble-3we2di:before{
    border-top-color:var(--outline-lightcolor)
}
#friends{
    background:var(--channels-darker)!important
}
.friends-table{
    background:var(--chat-color)!important;
    border-top:1px solid var(--outline-lightcolor)
}
.tab-bar-item.tab-bar-item-primary{
    background:linear-gradient(to bottom,#232323 0,#191919 100%)!important;
    border-radius:0!important;
    box-shadow:inset 0 0 0 1px #0a0a0a,inset 0 0 0 2px #323232;
    font-size:11px;
    padding:5px 15px 5px 15px!important;
    color:var(--text-color)!important
}
.tab-bar-item.tab-bar-item-primary:hover{
    background:linear-gradient(to bottom,#282828 0,#1e1e1e 100%)!important
}
.tab-bar-item.tab-bar-item-primary.selected{
    background:linear-gradient(to bottom,#1e1e1e 0,#0f0f0f 100%)!important;
    color:var(--primary-color)!important
}
.tab-bar-item{
    color:var(--text-color)!important
}
.tab-bar-item.selected{
    border-radius:0!important;
    background:var(--outline-lightcolor)!important;
    color:var(--primary-color)!important
}
.tab-bar-item:hover{
    border-radius:0!important;
    background:var(--outline-lightcolor)!important
}
.friends-table .friends-row:hover{
    border-radius:0!important;
    background:var(--outline-lightcolor)!important
}
.friends-table .friends-row .friends-column-actions .friends-action:hover{
    background-color:var(--outline-color)!important
}
.private-channels .channel.selected a,.private-channels .channel a:hover{
    background:var(--outline-lightcolor);
    color:var(--text-color)!important;
    margin-right:10px!important
}
.friend-table-add-wrapper .friend-table-add-header{
    background:var(--channels-darker)!important;
    border-bottom:1px solid var(--outline-lightcolor)!important;
    box-shadow:none!important;
    padding-top:10px
}
.friend-table-add-wrapper h2{
    font-size:12px!important
}
.friend-table-add-wrapper h3{
    font-size:11px!important
}
.friend-table-add-wrapper .friend-table-add-description{
    font-size:11px!important
}
.wrapper-3JPufy{
    padding-right:5px
}
.inner-2Y6JuD{
    border-radius:1px;
    border-color:var(--outline-lightcolor);
    background-color:var(--chat-color)
}
.wrapper-1cBijl{
    border-radius:0!important;
    background:var(--text-input)!important;
    box-shadow:inset 0 0 0 1px #323232,inset 0 0 0 2px #101010
}
.friend-table-suggestions-header{
    padding:20px 30px 16px!important
}
.btn{
    background:var(--primary-color)!important
}
.modal-3HD5ck{
    border-radius:0;
    background:var(--channels-darker)!important;
    box-shadow:inset 0 0 0 1px #0a0a0a,inset 0 0 0 2px #323232!important
}
.h4-AQvcAz{
    font-size:13px;
    color:var(--text-color)!important
}
.primary-jw0I4K{
    font-size:12px!important;
    color:var(--text-color)!important
}
.message-group-blocked{
    border-radius:0!important;
    background:var(--dropdown-color)!important
}
.message-group-blocked .message-group-blocked-btn{
    background:var(--channels-color)!important;
    font-size:11px
}
.mention{
    color:var(--primary-color)!important;
    background:var(--mention-color)!important
}
.popout{
    box-shadow:none!important;
    border:var(--outline-lightcolor)!important
}
.userPopout-3XzG_A{
    border-radius:1px;
    box-shadow:0 0 0 1px #323232,0 0 0 2px #0a0a0a!important
}
.headerPlaying-j0WQBV,.headerNormal-T_seeN{
    background:var(--channels-darker)!important
}
.activity-11LB_k{
    background:var(--primary-color)
}
.body-3iLsc4,.footer-1fjuF6{
    background:var(--channels-color)!important
}
.textRow-19NEd_{
    font-size:13px
}
.quickMessage-2XpSaN{
    border-radius:0!important;
    background:var(--text-input)!important;
    border:0;
    box-shadow:inset 0 0 0 1px #323232,inset 0 0 0 2px #101010;
    font-size:11px
}
.role-2irmRk{
    font-size:10px
}
.note-3kmerW textarea{
    border-radius:0!important;
    background:var(--text-input)!important;
    border:0;
    box-shadow:inset 0 0 0 1px #323232,inset 0 0 0 2px #101010;
    font-size:11px
}
.search-results-wrap{
    background:var(--channels-color)!important;
    border-left:1px solid var(--outline-lightcolor)
}
.search-header{
    box-shadow:none!important;
    background:var(--channels-darker)!important;
    border-bottom:1px solid var(--outline-lightcolor)
}
.search-header .tab.selected{
    color:var(--primary-color)!important;
    border-color:var(--primary-color)!important
}
.search-results-wrap .channel-separator .channel-name{
    background:none!important;
    font-size:13px
}
.search-results-wrap .search-result:before,.search-results-wrap .search-result:after{
    background:none!important
}
.search-results-wrap .search-result .hit{
    background:var(--outline-lightcolor)!important;
    border-radius:1px;
    border:1px solid var(--outline-color)!important;
    box-shadow:none!important
}
.search-popout{
    box-shadow:none!important;
    background:var(--channels-color);
    box-shadow:0 0 0 1px #323232,0 0 0 2px #0a0a0a!important;
    border-radius:0
}
.search-popout .option{
    font-size:13px;
    height:24px
}
.search-popout .option.selected:before{
    height:24px
}
.search-popout .option.selected{
    background:var(--outline-lightcolor)
}
.search-popout .search-option .filter,.option.history .answer{
    color:var(--text-darker)
}
.search-popout .option:after,.search-popout .option.selected:after{
    background:0
}
.search-popout .search-query{
    border-bottom:0
}
.system-message{
    font-size:13px
}
.topSectionNormal-2-vo2m{
    background:var(--channels-darker)!important
}
.body-3ND3kc{
    background:var(--channels-color)!important
}
.tabBar-2MuP6- .tab-bar-item.selected{
    border-color:var(--primary-color)!important;
    background:none!important
}
.tabBar-2MuP6- .tab-bar-item:hover{
    background:none!important
}
.topSectionPlaying-1J5E4n{
    background:var(--channels-darker)
}
.autocomplete-1vrmpx{
    background:var(--channels-darker)!important;
    border:1px solid var(--outline-lightcolor)
}
.selectorSelected-1_M1WV{
    border-radius:1px;
    background:var(--channels-color)!important
}
.buttonBrandInvertedDefault-uUmgsD{
    background:var(--primary-color)!important;
    color:#fff
}
.chat-3bRxxu .newMessagesBar-mujexs{
    background:var(--primary-color)!important
}
.unread-1xRYoj{
    background:var(--primary-color)!important
}
.emojiPicker-3m1S-j{
    background:none!important
}
.emojiPicker-3m1S-j .header-1nkwgG .search-bar{
    background:none!important
}
.emojiPicker-3m1S-j .stickyHeader-1SS0JU{
    background:0
}
.emojiPicker-3m1S-j .category-2U57w6{
    color:var(--primary-color)
}
.search-bar.search-bar-light .search-bar-inner{
    border-radius:0!important;
    background:var(--text-input)!important;
    box-shadow:inset 0 0 0 1px #323232,inset 0 0 0 2px #101010
}
.emojiPicker-3m1S-j .categories-1feg4n .item-16cXuq.selected-39BZ4S{
    border-bottom-color:var(--primary-color)
}
.emojiPicker-3m1S-j .scroller-3vODG7 .emojiItem-109bjA.selected-39BZ4S{
    background-color:var(--dropdown-color)
}
.search-bar input{
    font-size:12px!important
}
.form header{
    color:var(--primary-color)!important
}
.form-deprecated,.form.deprecated{
    background:var(--channels-darker)!important;
    box-shadow:inset 0 0 0 1px var(--outline-lightcolor)
}
.form-deprecated .form-inner,.form.deprecated .form-inner{
    background:none!important
}
.form-deprecated .form-actions,.form.deprecated .form-actions{
    background:none!important;
    border-color:var(--outline-lightcolor)
}
.create-guild-container.deprecated .action{
    background:var(--channels-color);
    border:1px solid var(--outline-lightcolor)
}
.create-guild-container.deprecated .action.join:hover .btn{
    background-color:var(--primary-color)!important
}
.form-deprecated .btn-default,.form.deprecated .btn-default,.form-deprecated .btn-default:hover,.form.deprecated .btn-default:hover{
    background:none!important;
    border-bottom:0;
    color:var(--text-color)!important
}
.create-guild-container.deprecated .join-server h5{
    font-size:14px;
    color:var(--primary-color)
}
.create-guild-container.deprecated p{
    font-size:12px
}
.bd-blue .create-guild-container .join-server .sample-link{
    font-size:13px
}
.guild-form li .control-group input[type=text]{
    padding-left:10px
}
.form.deprecated .control-group input[type=text]{
    border-radius:0!important;
    background:var(--text-input)!important;
    border:0;
    box-shadow:inset 0 0 0 1px #323232,inset 0 0 0 2px #101010;
    color:var(--text-color);
    font-size:12px
}
.form.deprecated .control-group input[type=text]:focus{
    border:0
}
.bd-blue .avatar-uploader-inner{
    background:var(--primary-color)!important
}
.regionSelect-3lf4eE .regionSelectInner-24f4Ce,.regionSelect-3lf4eE:hover .regionSelectInner-24f4Ce,.regionSelect-3lf4eE:hover button{
    border-radius:1px;
    border-color:var(--outline-lightcolor)
}
.regionSelect-3lf4eE button,.regionSelect-3lf4eE:hover button{
    border-radius:1px;
    border-color:var(--outline-lightcolor);
    color:var(--text-color);
    background:var(--channels-color)
}
.regionSelectModal-12e-57{
    background:var(--channels-darker)
}
.regionSelectModal-12e-57 .regionSelectModalOption-2DSIZ3{
    background:var(--channels-color);
    border:1px solid var(--outline-lightcolor)
}
.regionSelectModal-12e-57 .regionSelectModalOption-2DSIZ3:hover{
    border-color:var(--primary-color)
}
.message-group a{
    color:var(--link-color)!important
}
.wrapper-2NJDcI{
    background:#232529
}
.themed-popout{
    background:var(--channels-color)!important;
    border-radius:1px!important;
    border:1px solid var(--outline-lightcolor)!important
}
.themed-popout .header{
    background:var(--channels-darker)!important;
    box-shadow:none!important;
    border-bottom:1px solid var(--outline-lightcolor)
}
.themed-popout .footer{
    background:none!important;
    border-top:1px solid var(--outline-lightcolor)
}
.private-channel-recipients-invite .friend{
    background:var(--channels-color)!important
}
.search-bar .search-bar-inner{
    border-radius:0!important;
    background:var(--text-input)!important;
    box-shadow:inset 0 0 0 1px #323232,inset 0 0 0 2px #101010
}
.private-channel-recipients-invite .footer button{
    background:var(--primary-color)!important
}
.video-1FfuMD{
    background:var(--channels-color);
    border-bottom:1px solid var(--outline-lightcolor)
}
.footer-2yfCgX{
    background:none!important
}
.tiles-2aXG_k{
    background:var(--channels-color)!important
}
.selectorButtonSelected-1j4DmC,.buttonBrandFilled-3Mv0Ra,.buttonBrandFilled-3Mv0Ra:hover,.buttonBrandFilled-3Mv0Ra:active{
    background:var(--primary-color)
}
.imageSelected-4Kl81J{
    border-color:var(--primary-color)
}
.quickswitcher-3JagVE{
    background:var(--channels-darker)!important;
    border-radius:1px;
    border:1px solid var(--outline-lightcolor);
    box-shadow:none
}
.input-2VB9rf{
    border-radius:0!important;
    background:var(--text-input)!important;
    box-shadow:inset 0 0 0 1px #323232,inset 0 0 0 2px #101010!important;
    color:var(--text-color)!important
}
.note-3HfJZ5{
    margin-left:0
}
.note-3kmerW textarea{
    padding-top:6px;
    padding-left:10px
}
.form-deprecated .form-header,.form.deprecated .form-header{
    background:0
}
.wrapper-O5i5-0 .instantInviteModal-3vhcvC .form-header header{
    color:var(--primary-color);
    font-size:14px
}
.wrapper-O5i5-0 .instantInviteModal-3vhcvC .blurb-zsamaY{
    color:var(--text-color);
    font-size:11px
}
.wrapper-O5i5-0 .instantInviteModal-3vhcvC .checkbox .checkbox-inner span{
    border:0
}
.wrapper-O5i5-0 .instantInviteModal-3vhcvC .expireText-34b09Y{
    color:var(--text-color)
}
.cclipboardInputInner-1EXMA3{
    border-radius:0!important;
    background:var(--text-input)!important;
    box-shadow:inset 0 0 0 1px #323232,inset 0 0 0 2px #101010;
    border:none!important
}
.wrapper-O5i5-0 .instantInviteModal-3vhcvC .clipboardInputInner-RLx2hK input{
    background:0;
    font-size:16px;
    color:var(--primary-color)
}
.wrapper-O5i5-0 .instantInviteModal-3vhcvC .copy-3nFbq8{
    background:var(--primary-color);
    border:0;
    font-size:11px
}
.cclipboardInputInner-1EXMA3 button:first-of-type:before{
    background:none!important
}
.wrapper-O5i5-0{
    background:0
}
.Select-control,.Select-control:hover,.Select-control:active{
    border-radius:0!important;
    background:var(--text-input)!important;
    box-shadow:inset 0 0 0 1px #323232,inset 0 0 0 2px #101010;
    border:none!important
}
.has-value.Select--single>.Select-control .Select-value .Select-value-label,.has-value.is-pseudo-focused.Select--single>.Select-control .Select-value .Select-value-label,.has-value.Select--single>.Select-control .Select-value .Select-value-label{
    color:var(--text-color)
}
.wrapper-O5i5-0 .instantInviteModalAdvanced-3qJETM .checkbox .checkbox-inner span{
    border:0
}
.Select-option,.Select-option.is-focused{
    background:none!important;
    color:var(--text-color)!important
}
.Select-menu-outer{
    background:var(--channels-color);
    border:1px solid var(--outline-lightcolor)
}

.titleWrapper-1l0xT9 {
	background:var(--channels-darker);
}

.theme-dark .members-1998pB {
	background:var(--channels-darker);
}

.theme-dark .messageGroupWrapper-o-Zw7G {
	background-color: var(--chat-color);
	border-color: var(--outline-lightcolor);
	border-radius: 0px;
	border-width: 1px;
}

.theme-dark .divider-3gKybi.dividerRed-MKoLlr .dividerContent-2L12VI {
	color: var(--important-notification);
}

.theme-dark .divider-3gKybi.dividerRed-MKoLlr .dividerContent-2L12VI:after, .theme-dark .divider-3gKybi.dividerRed-MKoLlr .dividerContent-2L12VI:before {
	border-color: var(--important-notification-l);
}

/*               fixed bg                   */

.messages-3amgkR,
.searchBar-6Kv8R2,
.scroller-1JbKM,
.activityPanel-28dQGo,
.container-3baos1,
.scroller-2TZvBN,
.scroller-1JbKMe,
.scroller-2wx7Hm,
.bodyInner-245q0L,
.contentRegionScroller-26nc1e,
.sidebarRegionScroller-3MXcoP,
.container-1r6BKw.themed-ANHk51,
.friendsTable-133bsv,
.friendsTable-133bsv .friendsTableBody-1ZhKif,
.scroller-9moviB,
.emptyStateLarge-1nQX5A,
.theme-dark .layout-1cQCv2,
#bd-pub-button,
.customScroller-26gWhv,
.scroller-305q3I,
.header-2tA9Os,
.inner-ZyuQk0,
.theme-dark .footer-3rDWdC,
.container-1giJp5,
.platform-win .scroller-2TZvBN,
.scroller-zPkAnE,
.footer-1eyGBa,
.noResults-ZTbl5V, .scroller-hUf6zQ,
.theme-dark .messagesPopout-24nkyi
.markup-2BOw-j code.inline,
.barButtonBase-3UKlW2,
.uploadModal-2ifh8j,
.uploadModal-2ifh8j .footer-3mqk7D,
.emojiPicker-3m1S-j,
.listeningAlong-30wH70,
.bda-dark .emojiPicker-3m1S-j .category-2U57w6,
.emptyResultsWrap-3Kv0LQ,
.searchHeader-1l-wpR,
.measurement-36xDqs,
.panel-24C3ux,
.modalBody-LuOFny,
.perksModalContentWrapper-2HU6uL,
.scroller-5bBood {
    background: #0a0a0a!important;
}

.markup-2BOw-j pre code {
    box-shadow: 0 0 0 1px #3c3c3c,0 0 0 2px #282828,0 0 0 3px #3c3c3c,0 0 0 4px #0a0a0a;
    border-radius: 0px!important;
    transition: all ease-in 0.1s;
    background: var(--mention-color)!important;
}

.contextMenu-HLZMGh {
    box-shadow: 0 0 0 1px #3c3c3c,0 0 0 4px #282828,0 0 0 5px #3c3c3c,0 0 0 6px #0a0a0a!important;
    border-top: solid 2px var(--channels-text-selected)!important;
    border-radius: 0px!important;
    background: var(--mention-color)!important; 
}

/* bda-emojipicker */

.bda-dark .emojiPicker-3m1S-j {
    box-shadow: 0 0 0 1px #3c3c3c,0 0 0 4px #282828,0 0 0 5px #3c3c3c,0 0 0 6px #0a0a0a!important;
    border-radius: 0px!important;
    background: var(--mention-color)!important;  
}

.bda-dark .emojiPicker-3m1S-j:before {
    content:'';
    position:absolute;
    width:100%;
    height:2px;
    background:linear-gradient(to right,#37b1da 0,#c948cd 50%,#cce335 100%);
    top:0px;
    left:-1px;
}

.bda-dark .emojiPicker-3m1S-j .category-2U57w6 {
    background-color: var(--mention-color)!important;
}

/* blocked */

.wrapper-39oAo3 {
    box-shadow: 0 0 0 1px #3c3c3c,0 0 0 4px #282828,0 0 0 5px #3c3c3c,0 0 0 6px #0a0a0a!important;
    border-radius: 0px!important;
    background: var(--mention-color)!important;   
}

.wrapper-39oAo3:before {
    content:'';
    position:absolute;
    width:100%;
    height:2px;
    background:linear-gradient(to right,#37b1da 0,#c948cd 50%,#cce335 100%);
    top:10px;
    left:-1px; 
}

/* bottag */

.botTagRegular-2HEhHi {
    background-color: var(--primary-color);
}

.botTag-2WPJ74 {
    font-size: 12px!important;
}

/* add role gui */

.container-VSDcQc {
    box-shadow: 0 0 0 1px #3c3c3c,0 0 0 4px #282828,0 0 0 5px #3c3c3c,0 0 0 6px #0a0a0a!important;
    border-radius: 0px!important;
    background: var(--mention-color)!important;   
}

.container-VSDcQc .headerText-3i6A8K {
    font-size: 10px!important;
}

.theme-dark .row-rrHHJU {
    background-color: var(--mention-color);
}

.container-VSDcQc:before {
    content:'';
    position:absolute;
    width:100%;
    height:2px;
    background:linear-gradient(to right,#37b1da 0,#c948cd 50%,#cce335 100%);
    top:1px;
    left:-1px;
}

/* view profile text */

.avatarHintInner-Dco91E {
    font-size: 12px!important;
    font-weight: normal!important;
    text-transform: none!important;
}

/* gif selector */

.autocomplete-1vrmpx {
    box-shadow: 0 0 0 1px #3c3c3c,0 0 0 4px #282828,0 0 0 5px #3c3c3c,0 0 0 6px #0a0a0a!important;
    border-radius: 0px!important;
    background: var(--mention-color)!important;  
}

.autocomplete-1vrmpx:before {
    content:'';
    position:absolute;
    width:100%;
    height:2px;
    background:linear-gradient(to right,#37b1da 0,#c948cd 50%,#cce335 100%);
    top:0px;
    left:-1px; 
}

/* messages popout */ 

.theme-dark .messagesPopoutWrap-1MQ1bW {
    box-shadow: 0 0 0 1px #3c3c3c,0 0 0 4px #282828,0 0 0 5px #3c3c3c,0 0 0 6px #0a0a0a!important;
    border-radius: 0px!important;
    background: var(--mention-color)!important;  
}

.theme-dark .messagesPopoutWrap-1MQ1bW:before {
    content:'';
    position:absolute;
    width:100%;
    height:2px;
    background:linear-gradient(to right,#37b1da 0,#c948cd 50%,#cce335 100%);
    top:0px;
    left:-1px;   
}

.themedPopout-1TrfdI .header-2Kf7Yu{
    z-index: 0!important;
}


/* connection status */

.container-2x5lvQ {
    box-shadow: 0 0 0 1px #3c3c3c,0 0 0 4px #282828,0 0 0 5px #3c3c3c,0 0 0 6px #0a0a0a!important;
    border-radius: 0px!important;
    background: var(--mention-color)!important;  
}

.theme-dark .container-2x5lvQ .header-2C89wJ,
.theme-dark .container-2x5lvQ section {
    background: var(--mention-color)!important;
}

.theme-dark .container-2x5lvQ .header-2C89wJ:before {
    content:'';
    position:absolute;
    width:100%;
    height:2px;
    background:linear-gradient(to right,#37b1da 0,#c948cd 50%,#cce335 100%);
    top:0px;
    left:-1px;   
}

/* ----------- */

.contextMenu-HLZMGh:before {
    content:'';
    position:absolute;
    width:101%;
    height:2px;
    background:linear-gradient(to right,#37b1da 0,#c948cd 50%,#cce335 100%);
    top:-2px;
    left:-1px;
}

/* random button */

.selectorButtonSelected-336oUc {
    background-color: var(--primary-color)!important;
}

.container-3cGP6G {
    box-shadow: 0 0 0 1px #3c3c3c,0 0 0 4px #282828,0 0 0 5px #3c3c3c,0 0 0 6px #0a0a0a!important;
    border-radius: 0px!important;
    background: var(--mention-color)!important;
}

.container-3cGP6G:before {
    content:'';
    position:absolute;
    width:101%;
    height:2px;
    background:linear-gradient(to right,#37b1da 0,#c948cd 50%,#cce335 100%);
    top:-2px;
    left:-1px;  
}

.barButtonBase-3UKlW2 {
    background-color: var(--mention-color)!important;
    box-shadow: 0 0 0 1px #3c3c3c,0 0 0 4px #282828,0 0 0 5px #3c3c3c,0 0 0 6px #0a0a0a!important;
    border-radius: 0px!important;
    opacity: 1!important;
    color: whitesmoke!important;
}

.container-2ax-kl {
    font-size: 12px!important;
}

.role-2irmRk {
    border-radius: 0px!important;
}

.roleName-32vpEy {
    font-size: 12px!important;
}

.userSettingsAccount-2eMFVR div:nth-child(2)>div:nth-child(2)>.viewBody-2Qz-jg:hover {
	filter: blur(0)
}

.userSettingsAccount-2eMFVR div:nth-child(2)>div:nth-child(2)>.viewBody-2Qz-jg {
	filter: blur(5px);
	transition: 250ms filter ease-in-out
}

.content-3at_AU {
    margin: 1px;
}

.modeSelected-1zApJ_ .content-3at_AU, .modeSelected-1zApJ_:hover .content-3at_AU {
    border-radius: 0px!important;
    background: var(--mention-color)!important; 
}

.theme-dark .attachment-33OFj0 {
    box-shadow: 0 0 0 1px #3c3c3c,0 0 0 2px #282828,0 0 0 3px #3c3c3c,0 0 0 4px #0a0a0a;
    border-radius: 0px!important;
    background: var(--mention-color)!important;
}

.weightSemiBold-1WYsXZ {
    font-weight: 400!important;
    font-size: 14px!important;
}

.userPopout-3XzG_A.da-userPopout {
    box-shadow: 0 0 0 1px #3c3c3c,0 0 0 4px #282828,0 0 0 5px #3c3c3c,0 0 0 6px #0a0a0a!important;
    border-radius: 0px!important;
    background: var(--mention-color)!important; 
}

.userPopout-3XzG_A.da-userPopout:before {
    content:'';
    position:absolute;
    width:100%;
    height:2px;
    background:linear-gradient(to right,#37b1da 0,#c948cd 50%,#cce335 100%);
    top:0px;
    left:0px;
}

.activity-11LB_k {
    background-color: var(--channels-selected)!important;
}

.menu-Sp6bN1 {
    box-shadow: 0 0 0 1px #3c3c3c,0 0 0 4px #282828,0 0 0 5px #3c3c3c,0 0 0 6px #0a0a0a!important;
    border-radius: 0px!important;
    background: var(--mention-color)!important; 
}

.separator-2zcjq8 {
    width: auto!important;
}

.clickable-2ap7je .header-2o-2hj:hover, .selected-WP3kCM .header-2o-2hj {
    background-color: #0a0a0a!important;
}

.uploadModal-2ifh8j .inner-3nWsbo {
    border-color: var(--primary-color)!important;
}

.lookInverted-2D7oAl.colorBrand-3pXr91 {
    background-color: var(--primary-color)!important;
    color: whitesmoke!important;
}

.markup-2BOw-j code.inline {
    padding: 0em!important;
    background-color: #0a0a0a!important;
}

.container-3baos1 {
    margin-bottom: 0px!important;
}

.wrapper-1BJsBx.selected-bZ3Lue .childWrapper-anI2G9, .wrapper-1BJsBx .childWrapper-anI2G9 {
    background-color: var(--channels-color)!important;
    color: var(--primary-color)!important;
}

.selected-aXhQR6 .layout-2DM8Md {
    transition: text ease-in 0.1s;
    border-radius: 0px;
    background: var(--mention-color)!important;
    color: white;
}

.metadata-3WGS0M {
    color: #cbcbcb!important;
}

.modeConnected-2IEL4z .name-3_Dsmg, .modeConnected-2IEL4z:hover .name-3_Dsmg, .modeSelected-1zApJ_ .name-3_Dsmg {
    color: white;
}

.circleIconButton-jET_ig {
    color: #a0db15!important;
    background: #0a0a0a!important;
}

.layout-2DM8Md {
    transition: all ease-in 0.1s;
}

.theme-dark .placeholderWrapper-3FaLtZ {
    background: var(--mention-color)!important;
}

.mention {
    background: var(--chat-color)!important;
    color: var(--link-color)!important;
    text-shadow: 0 0 5px #a0db15!important;
    border-radius: 2px;
}

.lookFilled-1Gx00P.colorBrand-3pXr91 {
    background-color: #75a00d!important;
}

.name-3YKhmS, .tierTooltipTitle-1EIbL_ {
    color: whitesmoke!important;
}

.lookFilled-1Gx00P.colorGreen-29iAKY {
    background-color: var(--channels-text-selected)!important;
}

.children-19S4PO:after {
    display: none!important;
}

.markup-2BOw-j a {
    color: var(--link-color)!important;
    text-shadow: 0 0 5px var(--link-color)!important;
}

.membersGroup-v9BXpm {
    height: 45px!important;
}

.anchor-3Z-8Bb {
    color: #a0db15;
}

.cancelButton-3hVEV6, .downloadButton-23tKQp {
    color: #a0db15!important;
}

.expandedFolderBackground-2sPsd- {
    background-color: var(--dropdown-color);
}

.edited-DL9ECl {
    margin-left: 0.2px;
    margin-top: 0.03em;
}

.mediaBarGrabber-1FqnbN, .mediaBarProgress-1xaPtl, .mediaBarProgress-1xaPtl:after, .mediaBarProgress-1xaPtl:before {
    background-color: var(--link-color)!important;
}

.emptyResultsWrap-3Kv0LQ {
    color: #0a0a0a!important;
}

.theme-dark .messagesPopout-24nkyi,
.theme-dark .jumpButton-3DTcS_,
.theme-dark .messageGroupWrapper-o-Zw7G:hover .actionButtons-1sUUug {
    background-color: #0a0a0a!important;
    box-shadow: none;
}

.theme-dark .option-1l2vXE {
    background-color: #111;
}

.theme-dark .consent-1AQ-th, .theme-light .consent-1AQ-th {
    background-color: var(--link-color);
}

.blockquoteDivider-2hH8H6 {
    background-color: var(--link-color);
}

.base-PmTxvP {
    font-size: 10px!important;
}

.numberBadge-2s8kKX.base-PmTxvP.da-numberBadge {
    background-color: var(--link-color)!important;
    width: 20px;
}

.lowerBadge-29hYVK.da-lowerBadge {
    transform: translate(1px, 0px)!important;
}

/* LiveIcon. */

.live-2o_S8y {
    background-color: var(--primary-color)!important;
}

/* Chat(Input)box. */

.inner-zqa7da:before {
    content:'';
    position:absolute;
    width: 99.76%;
    height:2px;
    background:linear-gradient(to right,#37b1da 0,#c948cd 50%,#cce335 100%);
    top:1.8px;
    left:1px;
}

.button-2vd_v_,
.button-3AYNKb {
    padding: 4px!important;
    margin: 10px;
}
/*Update stuff*/

.form-2fGMdU:before{
    display:none;
}

  /* Discord Message box */
:root {
    --color-brand-lighter: #a2e427;
}
.input-cIJ7To,
.scrollableContainer-2NUZem {
    background-color: #141414;
    transition: background-color 0.2s ease, border-color 0.2s ease;
    border: 1px solid transparent;
    outline: none;
}
.input-cIJ7To:hover,
.scrollableContainer-2NUZem:hover {
    border-color: #96c83c!important;;
    background-color: #181818!important;;
      box-shadow: 0px 0px 3px 1px #96c83c;
}
.input-cIJ7To:focus-within,
.scrollableContainer-2NUZem:focus-within {
    background-color: #1f1f1f!important;;
    border-color: var(--color-brand-lighter)!important;
}
.scrollableContainer-2NUZem {
    border: 1px solid transparent;
    border-radius: 5px;
}
/*Change selected channel side color*/
.containerDefault--pIXnN.selected-3LIHYU {
    border-left: 1px solid #9fca2b;
    box-shadow: 0px 0px 3px 1px #96c83c!important;
}
/* Pings */
.numberBadge-2s8kKX {
  animation: animatedPing 1.3s infinite ease-in-out;
}
@keyframes animatedPing {
  0% {
    transform: rotate(-12deg);
  }
  50% {
    transform: rotate(12deg) scale(1.2);
  }
  100% {
    transform: rotate(-10deg);
  }
}
/* Hover Channels animated */
.mainContent-u_9PKf:hover {
  animation: UserModalButtons 0.5s normal ease;}
.mainContent-u_9PKf .noWrap-3jynv6 {width: 100px;opacity: 1;}
.mainContent-u_9PKf {transition: 0.2s;}
.mainContent-u_9PKf:hover {transition: 0.2;}
@keyframes UserModalButtons {
  0% {
    transform: translateY(0px);
  }
  45% {
    transform: translateY(-5px);
  }
  90% {
    transform: translateY(0px);
  }
}



#app-mount .privateChannels-1nO12o .searchBar-6Kv8R2 {
  position: absolute;
  bottom: 20px;
  right: 5px;
  height: 40px;
  width: 42px;
  border: none;
  border-radius: 40px;
  background: linear-gradient(to bottom right, var(--main-color, #323232), var(--hover-color, #323232));
  box-shadow: 2px 10px 10px var(--shadow, rgba(75, 75, 75, 0.399)) !important;
  overflow: hidden;
  cursor: pointer;
  transition: all .4s ease-in-out;
  pointer-events: all;
  padding: 0;
}

#app-mount .privateChannels-1nO12o .searchBar-6Kv8R2 .searchBarComponent-32dTOx {
  background-color: transparent !important;
}
/** 
* @name gamesense theme 
* @version 1.2 
* @description Fixed gamesense theme 
* @author Xyhlo#9766 
* @socials This is my instagram be nice and leave a like or a comment: maxyiiiss
*/
@import url('https://fonts.googleapis.com/css?family=Raleway');
@import url(https://codedotspectra.github.io/themes/mini-themes/settingsIcons.css);
:root{
     --title-gradient:linear-gradient(to right,#37b1da ,#c948cd ,#cce335, #37b1da);
     --primary-color:#75a00d;
     --background-secondary: #0a0a0a;
    --background-primary: #070707;
     --outline-color:#0a0a0a;
     --outline-lightcolor:#303030;
     --app-color:#0b0b0b;
     --channels-color:#111;
     --channeltextarea-background: #000;
     --channels-darker:#0c0c0c;
     --channels-selected:#191919;
     --channels-text-selected:#9fca2b;
     --chat-color:#0b0b0b;
     --mention-color:#1f1f1f;
     --scrollbar-bg:#202020;
     --scrollbar-thumb:#414141;
     --text-input:#191919;
     --dropdown-color:#232323;
     --link-color:#96c83c;
     --channel-radius:5px;
     --text-color:#cbcbcb;
     --text-darker:#b0b0b0;
     --font:'Verdana',Helvetica,Arial,sans-serif;
     --important-notification-l:#f84747;
     --important-notification:#d12020;
     
}
.search-1FM8Qc:not(.open-3y3yI_) .searchBar-zdmu7v {
     width: 27px;
     transition: 0.25s;
     background-color: transparent;
}
.search-1FM8Qc:not(.open-3y3yI_):hover .searchBar-zdmu7v {
     width: 240px;
     background-color: var(--background-tertiary);
}
.search-1FM8Qc:not(.open-3y3yI_) .iconContainer-1RqWJj {
     transform: scale(1.3);
     transition: 0.25s;
}
.search-1FM8Qc:not(.open-3y3yI_):hover .iconContainer-1RqWJj {
     transform: scale(1);
}
.icon-18rqoe {
     color: var(--text-normal)
}
.scrollableContainer-2NUZem {
     padding-right: 11px ;
}
.typeWindows-2-g3UY{
     animation: rgbTop 3s infinite linear;
    
}
@keyframes rgbTop {
     0% {
         background-position: 1920px;
         
    }
     100% {
         background-position: 0px;
         
    }
    
}
.scrollableContainer-2NUZem::-webkit-scrollbar {
     display: none;
    
}
.avatarHintInner-2HUAWj {
     font-size: 8px !important;
    
}

/* Change ping badge color */
.numberBadge-37OJ3S {
    background-color: #6e9601 !important
}

/*Remove Stage Discovery Tab*/
#private-channels [href=\"/discovery\"] {
    display: none
}

/*Remove Library Tab*/
#private-channels [href=\"/library\"] {
    display: none
}

/*Remove Nitro Tab*/
#private-channels [href=\"/store\"] {
    display: none
}

/*Unread channels rainbow wave*/
.wrapper-NhbLHG.modeUnread-3Cxepe .name-28HaxV {
     background-image: linear-gradient(to left,rgb(51, 255, 0), rgb(255, 230, 0), red, rgb(234, 0, 255), rgb(0, 140, 255), rgb(51, 255, 0));
     animation: gradient-border 3s linear infinite;
     background-size: 400% 100%;
     color: transparent !important;
     -webkit-background-clip: text;
     position: relative;
     z-index: 1;
    
}
@keyframes gradient-border {
     0%, 200% {
         background-position: 0 0;
         
    }
     99.999999999999999% {
         background-position: 130% 0;
         
    }
    
}
 .expandedFolderBackground-1cujaW,.expandedFolderIconWrapper-Huv7r{
    /*couleur fichier ouvert*/
     background-color:#0a0a0a!important;
    
}
.members-3WRCEx, .members-3WRCEx > .content-2a4AW9 {
     background: #0a0a0a !important;
    
}
#app-mount .wrapper-1Rf91z {
     background-color: #0a0a0a !important;
    
}

/*Change selected channel side color*/
.containerDefault-YUSmu3.selected-2TbFuo {
     border-left: 6px solid #9fca2b;
    
}
#app-mount .container-2nx-BQ, #app-mount .bd-switch-body {
     width: 20px;
     height: 20px;
     background: transparent !important;
     
}
 #app-mount .container-2nx-BQ .slider-32CRPX, #app-mount .bd-switch-body .bd-switch-slider {
     left: -6px !important;
     
}
 #app-mount .container-2nx-BQ .slider-32CRPX > rect, #app-mount .bd-switch-body .bd-switch-slider rect {
     height: 20px !important;
     width: 20px !important;
     x: 4px !important;
     y: 0px !important;
     rx: 5;
     fill: var(--background-tertiary);
     
}
.wrapper-1_HaEi::before {
    /*Guild wrapper background*/
     content: '';
     position: absolute;
     top: 0;
     left: 0;
     bottom: 0;
     right: 0;
     background: #0a0a0a;
     background-size: cover;
    
}
.tree-3agP2X, .scroller-3X7KbA,.wrapper-1_HaEi {
    /*Guild subcontainer*/
     background: transparent;
    
}

/*connections look cooler*/
.connectedAccount-2Jb-Z0:active{
     border-width: 1.2px 1.2px 1.2px 1.2px;
     transform: translateY(1px);
     transition: 0.1s;
    
}
.connectedAccount-2Jb-Z0{
     border: solid #151b27;
     border-width: 1.2px 1.2px 3px 1.2px;
     border-radius: 4px;
     transition: 0.1s;
    
}
.scrollableContainer-2NUZem {
     border: 1px solid #9fca2b;
     
}
 svg.homeIcon-FuNwkv{
     color:transparent;
    
}

/* Custom home icon */
#app-mount .listItemWrapper-KhRmzM .childWrapper-1j_1ub {
     background: url('https://i.ytimg.com/vi/meqVOjIO45A/maxresdefault.jpg') center/cover no-repeat;
    
}
.homeIcon-FuNwkv {
     display: none;
    
}
*{
     font-size: 15px!important;
     font-family:var(--font)!important;
}
strong{
     font-weight:normal;
}
a{
     color:var(--link-color);
}
body{
     font-family:var(--font)!important;
     background-color:var(--app-color) ;
}
input,textarea{
     font-family:var(--font)!important;
}
.wrapper-1Rf91z{
    background-color:#191919;
    
}
.appMount-2yBXZl{
     left:6px;
     top:6px;
     height:calc(100vh - 12px);
     width:calc(100vw - 12px);
     box-shadow:0 0 0 1px #3c3c3c,0 0 0 4px #282828,0 0 0 5px #3c3c3c,0 0 0 6px #0a0a0a;
     background-color:var(--channels-color);
}
.typeWindows-2-g3UY{
     height:25px;
     background:var(--primary-color);
     margin-top:-0.5px!important;
     margin-left:1px;
     margin-right:1px;
     background:var(--title-gradient);
     box-shadow:inset 0 -23px 0 0 var(--app-color),inset 0 -24px 0 0 rgba(0,0,0,0.5);
     opacity:1.0;
     z-index:50;
     border-bottom:1px solid var(--outline-lightcolor)
}
*/
.typeWindows-2-g3UY:hover{
    \theight:20px;
    \ttransition: all .6s;
    \topacity: 1;
    
}
*/
.winButton-iRh8-Z{
     top:2px!important
}
.wordmark-2u86JB{
     opacity:1.0;
     font-family:'Raleway'
}
.wordmark-2u86JB::before{
     content:'game';
     font-size:14px;
     z-index:1000;
     position:fixed;
     display:inline-block;
     color:var(--text-color);
     height:auto;
     top:12px;
     left:12px;
     background-color:transparent
}
.mention-1f5kbO {
     background-color: var(--primary-color)!important;
    
}
.wordmark-2u86JB::after{
     content:'sense';
     font-size:14px;
     z-index:1000;
     position:fixed;
     display:inline-block;
     color:var(--primary-color);
     height:auto;
     top:12px;
     left:52px;
     background-color:transparent
}
.winButtonClose-3Q8ZH5{
     height:33px;
    
}
.winButtonClose-3Q8ZH5:hover{
     background-color: transparent;
    
}
.winButtonMinMax-3RsPUg{
    height:33px;
    
}
.winButtonMinMax-3RsPUg:hover{
     background-color: transparent;
    
}
.wordmark-2u86JB svg{
     display:none
}
.theme-dark .guildsWrapper{
     background:var(--channels-darker);
     box-shadow:inset -1px 0 0 0 #303030,inset -2px 0 0 0 #000
}
.guildsWrapper .guildsAdd-21_Id{
     border-radius:0;
     background:var(--chat-color);
     border:1px dashed var(--outline-lightcolor);
     color:var(--outline-lightcolor)
}
.guildsWrapper-1Rf91z .guildsAdd-21_Id:hover{
     color:var(--text-color);
     border-color:var(--text-color)
}
.guildsWrapper-1Rf91z .guildsAdd-21_Id-inner{
     top:-2px
}
.guildsWrapper-1Rf91z .guilds-1q_RqH .guilds-1q_RqH+.guilds-1q_RqH{
     margin-bottom:25px;
     margin-top:25px
}
.guildInner-3DSoA4{
     border-radius:0!important
}
.guildsWrapper-1Rf91z .guilds-1q_RqH .guild-1EfMGQ+.guild-1EfMGQ{
     margin-top:25px
}
.guildsWrapper-1Rf91z .guilds-1q_RqH .friendsOnline-_wi_fM{
     padding-bottom:10px;
     font-size:9px
}
.guildsWrapper-1Rf91z .guilds-1q_RqH .guild-1EfMGQ.selected-ML3OIq:before{
     box-shadow:0 1px 0 0 #303030,-1px 2px 0 0 #000,0 -1px 0 0 #303030,-1px -2px 0 0 #000;
     background:var(--channels-color);
     border-radius:0;
     height:70px;
     margin-top:-35px;
     width:75px;
     -webkit-transition:none;
     transition:none
}
.guildsWrapper-1Rf91z .guilds-1q_RqH .guild-1EfMGQ .guildInner-3DSoA4{
     background:var(--chat-color)!important
}
.guildsWrapper-1Rf91z .guilds-1q_RqH .guild-1EfMGQ.selected-ML3OIq .guildInner-3DSoA4 a{
     background-color:var(--primary-color)!important;
     transition:all .3s ease
}
.guildsWrapper-1Rf91z .guilds-1q_RqH .guild-1EfMGQ.selected-ML3OIq .guildInner-3DSoA4{
     background-color:var(--primary-color)!important;
     transition:all .3s ease
}
.guildInner-3DSoA4{
     background-color:var(--primary-color);
     border-radius:var(--channel-radius)!important;
     transition:all .3s ease
}
.guildInner-3DSoA4:hover{
     background-color:var(--primary-color)!important;
     transition:all .3s ease
}
.guild-1EfMGQ.active .guildInner-3DSoA4{
     background:var(--primary-color)!important
}
.guildsWrapper-1Rf91z .guildseparator-1X4GQ1{
     display:none
}
.guildsAdd-21_IdK {
    \tborder-radius: 10%;
    
}
.avatar-large,.avatar-profile,.avatar-small,.avatar-xlarge,.avatar-xsmall,.avatar-xxlarge{
     border-radius:var(--channel-radius)!important
}
.avatarHint-1qgaV3{
    \tborder-radius:var(--channel-radius)!important
}
.container-PNkimc{
     background:none!important
}
.base-2jDfDU{
     border-radius:0!important
}
.header-2o-2hj{
     background:var(--channels-darker);
     box-shadow:none!important;
     border-bottom:1px solid var(--outline-lightcolor)
}
.header-2o-2hj:hover{
     background:var(--channels-selected)
}
.container-1UB9sr{
     border-top:1px solid var(--outline-lightcolor);
     border-bottom:0;
     background:var(--chat-color);
     font-size:11px;
     padding:5px 10px 5px 10px
}
.channels-Ie2l6A.vertical-V37hAW.flex-3BkGQD.directionColumn-3pi1nm {
     background:var(--channels-color);
     border-right:1px solid var(--outline-lightcolor)
}
.name-3M0b8v{
     font-size:13px;
     font-weight:700
}
.contentSelectedText-3wUhMi{
     background:var(--channels-selected)
}
.nameSelectedText-sp_EUw,.nameSelectedVoice-1qSph5,svg.colorSelectedText-1y4Wvs.icon-sxakjD,svg.colorSelectedVoice-Xcb_9R.icon-sxakjD{
     color:var(--channels-text-selected)!important;
     opacity:1
}
.theme-dark .member-3W1lQa:hover .content-OzHfo4, .theme-dark .member-3W1lQa.popout-open .content-OzHfo4, .theme-dark .member-3W1lQa.popout-open:hover .content-OzHfo4 {
    \tbackground:var(--channels-selected)
}
.contentHoveredText-2D9B-x,.contentHoveredVoice-3p_NEO,.contentHoveredVoice-3p_NEO:active,.contentSelectedVoice-1WDIBM:active{
     background:none!important
}
.container-2Thooq{
     background:var(--channels-darker);
     border-top:1px solid var(--outline-lightcolor)
}
.popout{
     background:var(--dropdown-color)!important;
     border:solid 1px var(--outline-color)!important;
     border-radius:1px
}
.small-popout-box{
     background:var(--dropdown-color)!important;
     border:solid 1px var(--outline-color)!important;
     border-radius:1px
}
.theme-dark .messagesPopoutWrap-1MQ1bW .footer-1kmXd4 {
     background: var(--channels-darker)!important;
    
}
.theme-dark .messagesPopoutWrap-1MQ1bW {
     border-radius: 1px;
     background: var(--channels-color)!important;
     box-shadow: 0 0 0 1px #323232,0 0 0 2px #0a0a0a!important;
    
}
.theme-dark .messagesPopoutWrap-1MQ1bW .header-ykumBX {
     -webkit-box-shadow: 0 2px 3px 0 rgba(0,0,0,20%);
     background-color: #35393e;
     box-shadow: 0 2px 3px 0 rgba(0,0,0,.2);
     background: var(--channels-darker)!important;
    
}
.option-popout .btn-item,.option-popout .btn-item:hover{
     color:var(--text-color)
}
.contextMenu-HLZMGh{
     background:var(--dropdown-color)!important;
     border:solid 1px var(--outline-color)!important;
     border-radius:1px;
     box-shadow:none!important;
}
.item-1Yvehc{
     font-size:11px!important
}
.item-1Yvehc:hover{
     background:var(--outline-lightcolor)!important;
     border-radius:0
}
.itemSubMenu-1vN_Yn{
     background-color:var(--dropdown-color)!important
}
.menu-Sp6bN1{
     border-radius:1px;
    \tbackground:var(--chat-color)!important;
    \tbox-shadow:0 0 0 1px #323232,0 0 0 2px #0a0a0a!important;
    
}
.item-1GzJrl{
     color:var(--text-color);
     font-size:11px!important
}
.item-1GzJrl:hover{
     border-radius:0!important;
     color:var(--text-color);
     background:var(--outline-lightcolor)!important
}
.separator-2zcjq8{
     border-color:var(--outline-lightcolor)!important;
     width:100%
}
.title-3qD0b-,.titleCall-_b9o8P{
     background:var(--channels-darker)!important;
     box-shadow:inset 0 -1px 0 var(--outline-lightcolor)!important
}
.channelName-3stJzi{
     font-size:13px;
     color:var(--text-color)!important
}
.channelName-3stJzi svg{
     width:14px;
     color:var(--text-color)
}
.channelIcon-MsmKOO{
     top:4px
}
.topic-2QX7LI{
     font-size:11px
}
.messagesWrapper-3lZDfY {
     background:none!important
}
.chat-3bRxxu>.content-yTz4x3{
     background:var(--chat-color)!important
}
.embedPill-1Zntps{
     background:var(--primary-color)!important
}
.embedInner-1-fpTo{
     background:var(--channels-darker)!important;
     border-radius:1px!important;
     border-color:var(--outline-lightcolor)!important
}
.message-group{
     padding:15px 0
}
.message-group h2 strong{
     font-size:13px
}
.timestampCozy-2hLAPV{
     font-size:9px
}
.markup-eYLPri{
     font-size:11px;
     line-height:1.4em
}
.markup-eYLPri pre{
     border-radius:1px!important;
     border:none!important;
     box-shadow:0 0 0 1px #323232,0 0 0 2px #101010!important
}
.markup-eYLPri pre code{
     font-size:13px;
     background:var(--dropdown-color)!important
}
.hljs-section{
     color:var(--primary-color)!important
}
.theme-dark .divider-3gKybi.dividerRed-MKoLlr .dividerContent-2L12VI>span {
     background:#113!important
}
.theme-dark .divider-3gKybi.dividerRed-MKoLlr .dividerContent-2L12VI:after, .theme-dark .divider-3gKybi.dividerRed-MKoLlr .dividerContent-2L12VI:before {
    background:var(--important-notification)!important;
    border-color: transparent !important;
    
}
.theme-dark .divider-3gKybi span {
    \tbackground:0b0b0b!important
}
.imageWrapper-oMkQl4{
     border-radius:3px
}
.chat-3bRxxu form{
     background:none!important;
     box-shadow:none!important
}
.inner-zqa7da{
     border-radius:0!important;
     background:var(--text-input)!important;
     box-shadow:inset 0 0 0 1px #323232,inset 0 0 0 2px #101010
}
.channelTextArea-rNsIhG .inner-zqa7da .textArea-2Spzkt{
     font-size:11px;
     line-height: 1.6rem;
    
}
.theme-dark .channelTextArea-rNsIhG {
    \tborder-top:none;
    
}
.innerEnabled-3g80kR .textArea-2Spzkt{
     font-size:11px;
     line-height:.80rem;
     margin:12px 2px 2px 0;
     padding:5px 38px 8px 10px
}
.textAreaEnabled-3vQ5WZ{
     padding:5px 38px 8px 0
}
.typing-2GQL18{
     background:none!important;
     font-size:8px!important;
     padding-left:1px
}
.typing-2GQL18 .ellipsis-1e7x0D{
     display:none
}
.scroller-2FKFPG.members-3WRCEx{
     background:var(--channels-darker)!important;
     border-left:solid 1px var(--outline-lightcolor);
     color:red
}
.image-33JSyf{
    \tborder-radius:var(--channel-radius)!important
}
.mask-3OgeRz{
    \t-webkit-mask: none;
    
}
::-webkit-scrollbar-thumb{
     border:none!important;
     border-radius:0!important;
     background:#414141!important
}
::-webkit-scrollbar{
     width:6px!important
}
::-webkit-scrollbar-track-piece{
     border:none!important;
     border-radius:0!important;
     background:#2d2d2d!important
}
.scroller-kQBbkU::-webkit-scrollbar{
     border:none!important;
     border-radius:0!important;
     background:#414141!important;
     height:100px!important;
}
.scroller-wrap .scroller::-webkit-scrollbar{
     width:6px!important
}
.scrollerWrap-2lJEkd .scroller::-webkit-scrollbar-track-piece{
     border:none!important;
     border-radius:0!important;
     background:#2d2d2d!important
}
.scrollerWrap-2lJEkd.scroller::-webkit-scrollbar-thumb{
     border:none!important;
     border-radius:0!important;
     background:#414141!important
}
.scrollerWrap-2lJEkd .scroller::-webkit-scrollbar{
     width:6px!important
}
.scrollerWrap-2lJEkd .scroller::-webkit-scrollbar-track-piece{
     border:none!important;
     border-radius:0!important;
     background:#2d2d2d!important
}
.tooltip,.tooltip.tooltip-black,.tipsy-inner{
     border-radius:1px!important
}
.bd-blue .tooltip-red,.tooltip.tooltip-red{
     background-color:var(--important-notification)
}
.bd-blue .tooltip-red.tooltip-top:after{
     border-top-color:var(--important-notification)
}
.bd-blue .tooltip-red.tooltip-left:after{
     border-left-color:var(--important-notification)
}
.bd-blue .tooltip-red.tooltip-bottom:after{
     border-bottom-color:var(--important-notification)
}
.bd-blue .tooltip-red.tooltip-right:after,.tooltip.tooltip-red.tooltip-right:after{
     border-right-color:var(--important-notification)
}
.tooltip.tooltip-right:after,.tooltip.tooltip-left:after{
     margin-top:-8px
}
.tooltip.tooltip-brand,.tooltip.tooltip-black,.tipsy-inner{
     background:var(--channels-darker)!important;
     border:solid 1px var(--outline-lightcolor)!important;
     border-radius:1px;
     padding:5px 10px;
     font-size:11px;
     font-weight:400;
     line-height:14px;
     text-align:center
}
.tooltip.tooltip-brand.tooltip-right:after,.tooltip.tooltip-black.tooltip-right:after{
     border-radius:0;
     border-right:8px solid var(--outline-lightcolor)!important;
     border-top:8px solid transparent!important;
     border-bottom:8px solid transparent!important
}
.tooltip.tooltip-brand.tooltip-top:after,.tooltip.tooltip-black.tooltip-top:after,.tipsy-se .tipsy-inner:after{
     border-radius:0;
     border-right:8px solid transparent!important;
     border-top:8px solid var(--outline-lightcolor)!important;
     border-left:8px solid transparent!important
}
.tooltip.tooltip-brand.tooltip-left:after,.tooltip.tooltip-black.tooltip-left:after{
     border-radius:0;
     border-left:8px solid var(--outline-lightcolor)!important;
     border-top:8px solid transparent!important;
     border-bottom:8px solid transparent!important
}
.tooltip.tooltip-brand.tooltip-bottom:after,.tooltip.tooltip-black.tooltip-bottom:after{
     border-radius:0;
     border-right:8px solid transparent!important;
     border-bottom:8px solid var(--outline-lightcolor)!important;
     border-left:8px solid transparent!important
}
.checkbox{
     width:8px;
     height:8px;
     background:#4c4c4c;
     background:linear-gradient(to bottom,#4c4c4c 0,#333 100%);
     border-radius:0!important;
     border:1px solid var(--outline-color)
}
.checkbox .checkbox-inner{
     height:8px;
     width:8px;
     border:0
}
.checkbox .checkbox-inner span{
     border:0;
     border-radius:0;
     background:linear-gradient(to bottom,#4c4c4c 0,#333 100%)
}
.checkbox .checkbox-inner input[type=checkbox]:checked+span{
     background:linear-gradient(to bottom,#9cc728 0,#7aa506 100%);
     transition:5.0
}
.checkbox .checkbox-inner input[type=checkbox]:checked+span:after{
     content:none
}
.checkbox .checkbox-inner+span{
     white-space:nowrap;
     color:var(--text-color);
     font-size:11px
}
.grabber-2GQyvM{
     border-radius:5px!important;
     margin-left:-6px!important
}
.bar-1Bhnl9{
     background:linear-gradient(to bottom,#343434 0,#444 100%)!important;
     border-radius:0!important;
     border:1px solid var(--outline-color)
}
.barFill-2Bh7CX{
     background:linear-gradient(to bottom,#99c427 0,#699404 100%)!important
}
.bubble-3we2di{
     background:var(--channels-darker)!important;
     border:solid 1px var(--outline-lightcolor)!important;
     border-radius:1px;
     font-size:10px;
     color:var(--text-color)
}
.bubble-3we2di:before{
     border-top-color:var(--outline-lightcolor)
}
#friends{
     background:var(--channels-darker)!important
}
.friends-table{
     background:var(--chat-color)!important;
     border-top:1px solid var(--outline-lightcolor)
}
.tab-bar-item.tab-bar-item-primary{
     background:linear-gradient(to bottom,#232323 0,#191919 100%)!important;
     border-radius:0!important;
     box-shadow:inset 0 0 0 1px #0a0a0a,inset 0 0 0 2px #323232;
     font-size:11px;
     padding:5px 15px 5px 15px!important;
     color:var(--text-color)!important
}
.tab-bar-item.tab-bar-item-primary:hover{
     background:linear-gradient(to bottom,#282828 0,#1e1e1e 100%)!important
}
.tab-bar-item.tab-bar-item-primary.selected{
     background:linear-gradient(to bottom,#1e1e1e 0,#0f0f0f 100%)!important;
     color:var(--primary-color)!important
}
.tab-bar-item{
     color:var(--text-color)!important
}
.tab-bar-item.selected{
     border-radius:0!important;
     background:var(--outline-lightcolor)!important;
     color:var(--primary-color)!important
}
.tab-bar-item:hover{
     border-radius:0!important;
     background:var(--outline-lightcolor)!important
}
.friends-table .friends-row:hover{
     border-radius:0!important;
     background:var(--outline-lightcolor)!important
}
.friends-table .friends-row .friends-column-actions .friends-action:hover{
     background-color:var(--outline-color)!important
}
.private-channels .channel.selected a,.private-channels .channel a:hover{
     background:var(--outline-lightcolor);
     color:var(--text-color)!important;
     margin-right:10px!important
}
.friend-table-add-wrapper .friend-table-add-header{
     background:var(--channels-darker)!important;
     border-bottom:1px solid var(--outline-lightcolor)!important;
     box-shadow:none!important;
     padding-top:10px
}
.friend-table-add-wrapper h2{
     font-size:12px!important
}
.friend-table-add-wrapper h3{
     font-size:11px!important
}
.friend-table-add-wrapper .friend-table-add-description{
     font-size:11px!important
}
.wrapper-1xW8FI{
     padding-right:5px
}
.inner-1lPVFp{
     border-radius:1px;
     border-color:var(--outline-lightcolor);
     background-color:var(--chat-color)
}
.wrapper-1cBijl{
     border-radius:0!important;
     background:var(--text-input)!important;
     box-shadow:inset 0 0 0 1px #323232,inset 0 0 0 2px #101010
}
.friend-table-suggestions-header{
     padding:20px 30px 16px!important
}
.btn{
     background:var(--primary-color)!important
}
.modal-3HD5ck{
     border-radius:0;
     background:var(--channels-darker)!important;
     box-shadow:inset 0 0 0 1px #0a0a0a,inset 0 0 0 2px #323232!important
}
.h4-AQvcAz{
     font-size:13px;
     color:var(--text-color)!important
}
.primary-jw0I4K{
     font-size:12px!important;
     color:var(--text-color)!important
}
.message-group-blocked{
     border-radius:0!important;
     background:var(--dropdown-color)!important
}
.message-group-blocked .message-group-blocked-btn{
     background:var(--channels-color)!important;
     font-size:11px
}
.mention{
     color:var(--primary-color)!important;
     background:var(--mention-color)!important
}
.popout{
     box-shadow:none!important;
     border:var(--outline-lightcolor)!important
}
.userPopout-3XzG_A{
     border-radius:1px;
     box-shadow:0 0 0 1px #323232,0 0 0 2px #0a0a0a!important
}
.headerPlaying-j0WQBV,.headerNormal-T_seeN{
     background:var(--channels-darker)!important
}
.activity-11LB_k{
     background:var(--primary-color)
}
.body-3iLsc4,.footer-1fjuF6{
     background:var(--channels-color)!important
}
.textRow-1sENuL{
     font-size:13px
}
.quickMessage-2XpSaN{
     border-radius:0!important;
     background:var(--text-input)!important;
     border:0;
     box-shadow:inset 0 0 0 1px #323232,inset 0 0 0 2px #101010;
     font-size:11px
}
.role-2irmRk{
     font-size:10px
}
.note-3kmerW textarea{
     border-radius:0!important;
     background:var(--text-input)!important;
     border:0;
     box-shadow:inset 0 0 0 1px #323232,inset 0 0 0 2px #101010;
     font-size:11px
}
.search-results-wrap{
     background:var(--channels-color)!important;
     border-left:1px solid var(--outline-lightcolor)
}
.search-header{
     box-shadow:none!important;
     background:var(--channels-darker)!important;
     border-bottom:1px solid var(--outline-lightcolor)
}
.search-header .tab.selected{
     color:var(--primary-color)!important;
     border-color:var(--primary-color)!important
}
.search-results-wrap .channel-separator .channel-name{
     background:none!important;
     font-size:13px
}
.search-results-wrap .search-result:before,.search-results-wrap .search-result:after{
     background:none!important
}
.search-results-wrap .search-result .hit{
     background:var(--outline-lightcolor)!important;
     border-radius:1px;
     border:1px solid var(--outline-color)!important;
     box-shadow:none!important
}
.search-popout{
     box-shadow:none!important;
     background:var(--channels-color);
     box-shadow:0 0 0 1px #323232,0 0 0 2px #0a0a0a!important;
     border-radius:0
}
.search-popout .option{
     font-size:13px;
     height:24px;
}
.search-popout .option.selected:before{
     height:24px;
}
.search-popout .option.selected{
     background:var(--outline-lightcolor);
}
.search-popout .search-option .filter,.option.history .answer{
     color:var(--text-darker);
}
.search-popout .option:after,.search-popout .option.selected:after{
     background:0;
}
.search-popout .search-query{
     border-bottom:0;
}
.system-message{
     font-size:13px;
}
.topSectionNormal-2-vo2m{
     background:var(--channels-darker)!important;
}
.body-3ND3kc{
     background:var(--channels-color)!important;
}
.tabBar-2MuP6- .tab-bar-item.selected{
     border-color:var(--primary-color)!important;
     background:none!important;
}
.tabBar-2MuP6- .tab-bar-item:hover{
     background:none!important;
}
.topSectionPlaying-1J5E4n{
     background:var(--channels-darker);
}
.autocomplete-3NRXG8{
     background:var(--channels-darker)!important;
     border:1px solid var(--outline-lightcolor);
}
.selectorSelected-1_M1WV{
     border-radius:1px;
     background:var(--channels-color)!important;
}
.buttonBrandInvertedDefault-uUmgsD{
     background:var(--primary-color)!important;
     color:#fff
}
.chat-3bRxxu .newMessagesBar-mujexs{
     background:var(--primary-color)!important
}
.unreadBar-elBRZx{
     background:var(--primary-color)!important
}
.emojiPicker-3m1S-j{
     background:none!important
}
.emojiPicker-3m1S-j .header-1nkwgG .search-bar{
     background:none!important
}
.emojiPicker-3m1S-j .stickyHeader-1SS0JU{
     background:0
}
.emojiPicker-3m1S-j .category-2U57w6{
     color:var(--primary-color)
}
.search-bar.search-bar-light .search-bar-inner{
     border-radius:0!important;
     background:var(--text-input)!important;
     box-shadow:inset 0 0 0 1px #323232,inset 0 0 0 2px #101010
}
.emojiPicker-3m1S-j .categories-1feg4n .item-16cXuq.selected-39BZ4S{
     border-bottom-color:var(--primary-color)
}
.emojiPicker-3m1S-j .scroller-3vODG7 .emojiItem-109bjA.selected-39BZ4S{
     background-color:var(--dropdown-color)
}
.search-bar input{
     font-size:12px!important
}
.form header{
     color:var(--primary-color)!important
}
.form-deprecated,.form.deprecated{
     background:var(--channels-darker)!important;
     box-shadow:inset 0 0 0 1px var(--outline-lightcolor)
}
.form-deprecated .form-inner,.form.deprecated .form-inner{
     background:none!important
}
.form-deprecated .form-actions,.form.deprecated .form-actions{
     background:none!important;
     border-color:var(--outline-lightcolor)
}
.create-guild-container.deprecated .action{
     background:var(--channels-color);
     border:1px solid var(--outline-lightcolor)
}
.create-guild-container.deprecated .action.join:hover .btn{
     background-color:var(--primary-color)!important
}
.form-deprecated .btn-default,.form.deprecated .btn-default,.form-deprecated .btn-default:hover,.form.deprecated .btn-default:hover{
     background:none!important;
     border-bottom:0;
     color:var(--text-color)!important
}
.create-guild-container.deprecated .join-server h5{
     font-size:14px;
     color:var(--primary-color)
}
.create-guild-container.deprecated p{
     font-size:12px
}
.bd-blue .create-guild-container .join-server .sample-link{
     font-size:13px
}
.guild-form li .control-group input[type=text]{
     padding-left:10px
}
.form.deprecated .control-group input[type=text]{
     border-radius:0!important;
     background:var(--text-input)!important;
     border:0;
     box-shadow:inset 0 0 0 1px #323232,inset 0 0 0 2px #101010;
     color:var(--text-color);
     font-size:12px
}
.form.deprecated .control-group input[type=text]:focus{
     border:0
}
.bd-blue .avatar-uploader-inner{
     background:var(--primary-color)!important
}
.regionSelect-3lf4eE .regionSelectInner-24f4Ce,.regionSelect-3lf4eE:hover .regionSelectInner-24f4Ce,.regionSelect-3lf4eE:hover button{
     border-radius:1px;
     border-color:var(--outline-lightcolor)
}
.regionSelect-3lf4eE button,.regionSelect-3lf4eE:hover button{
     border-radius:1px;
     border-color:var(--outline-lightcolor);
     color:var(--text-color);
     background:var(--channels-color)
}
.regionSelectModal-12e-57{
     background:var(--channels-darker)
}
.regionSelectModal-12e-57 .regionSelectModalOption-2DSIZ3{
     background:var(--channels-color);
     border:1px solid var(--outline-lightcolor)
}
.regionSelectModal-12e-57 .regionSelectModalOption-2DSIZ3:hover{
     border-color:var(--primary-color)
}
.message-group a{
     color:var(--link-color)!important
}
.wrapper-2NJDcI{
     background:#232529
}
.themed-popout{
     background:var(--channels-color)!important;
     border-radius:1px!important;
     border:1px solid var(--outline-lightcolor)!important
}
.themed-popout .header{
     background:var(--channels-darker)!important;
     box-shadow:none!important;
     border-bottom:1px solid var(--outline-lightcolor)
}
.themed-popout .footer{
     background:none!important;
     border-top:1px solid var(--outline-lightcolor)
}
.private-channel-recipients-invite .friend{
     background:var(--channels-color)!important
}
.search-bar .search-bar-inner{
     border-radius:0!important;
     background:var(--text-input)!important;
     box-shadow:inset 0 0 0 1px #323232,inset 0 0 0 2px #101010;
}
.private-channel-recipients-invite .footer button{
     background:var(--primary-color)!important;
}
.video-eAcneW{
     background:var(--channels-color);
     border-bottom:1px solid var(--outline-lightcolor)
}
.footer-2yfCgX{
     background:none!important
}
.tiles-2aXG_k{
     background:var(--channels-color)!important
}
.selectorButtonSelected-1j4DmC,.buttonBrandFilled-3Mv0Ra,.buttonBrandFilled-3Mv0Ra:hover,.buttonBrandFilled-3Mv0Ra:active{
     background:var(--primary-color)
}
.imageSelected-4Kl81J{
     border-color:var(--primary-color)
}
.quickswitcher-pKcM9U{
     background:var(--channels-darker)!important;
     border-radius:1px;
     border:1px solid var(--outline-lightcolor);
     box-shadow:none
}
.input-3r5zZY{
     border-radius:0!important;
     background:var(--text-input)!important;
     box-shadow:inset 0 0 0 1px #323232,inset 0 0 0 2px #101010!important;
     color:var(--text-color)!important
}
.note-3HfJZ5{
     margin-left:0
}
.note-3kmerW textarea{
     padding-top:6px;
     padding-left:10px
}
.form-deprecated .form-header,.form.deprecated .form-header{
     background:0
}
.wrapper-O5i5-0 .instantInviteModal-3vhcvC .form-header header{
     color:var(--primary-color);
     font-size:14px
}
.wrapper-O5i5-0 .instantInviteModal-3vhcvC .blurb-zsamaY{
     color:var(--text-color);
     font-size:11px
}
.wrapper-O5i5-0 .instantInviteModal-3vhcvC .checkbox .checkbox-inner span{
     border:0
}
.wrapper-O5i5-0 .instantInviteModal-3vhcvC .expireText-34b09Y{
     color:var(--text-color)
}
.cclipboardInputInner-1EXMA3{
     border-radius:0!important;
     background:var(--text-input)!important;
     box-shadow:inset 0 0 0 1px #323232,inset 0 0 0 2px #101010;
     border:none!important
}
.wrapper-O5i5-0 .instantInviteModal-3vhcvC .clipboardInputInner-RLx2hK input{
     background:0;
     font-size:16px;
     color:var(--primary-color)
}
.wrapper-O5i5-0 .instantInviteModal-3vhcvC .copy-3nFbq8{
     background:var(--primary-color);
     border:0;
     font-size:11px
}
.cclipboardInputInner-1EXMA3 button:first-of-type:before{
     background:none!important
}
.wrapper-O5i5-0{
     background:0
}
.Select-control,.Select-control:hover,.Select-control:active{
     border-radius:0!important;
     background:var(--text-input)!important;
     box-shadow:inset 0 0 0 1px #323232,inset 0 0 0 2px #101010;
     border:none!important
}
.has-value.Select--single>.Select-control .Select-value .Select-value-label,.has-value.is-pseudo-focused.Select--single>.Select-control .Select-value .Select-value-label,.has-value.Select--single>.Select-control .Select-value .Select-value-label{
     color:var(--text-color)
}
.wrapper-O5i5-0 .instantInviteModalAdvanced-3qJETM .checkbox .checkbox-inner span{
     border:0
}
.Select-option,.Select-option.is-focused{
     background:none!important;
     color:var(--text-color)!important
}
.Select-menu-outer{
     background:var(--channels-color);
     border:1px solid var(--outline-lightcolor)
}
.titleWrapper-1l0xT9 {
    \tbackground:var(--channels-darker);
    
}
.theme-dark .members-3WRCEx {
    \tbackground:var(--channels-darker);
    
}
.theme-dark .messageGroupWrapper-o-Zw7G {
    tbackground-color: var(--chat-color);
    tborder-color: var(--outline-lightcolor);
    tborder-radius: 0px;
    border-width: 1px;
    
}
.theme-dark .divider-3gKybi.dividerRed-MKoLlr .dividerContent-2L12VI {
    color: var(--important-notification);
    
}
.theme-dark .divider-3gKybi.dividerRed-MKoLlr .dividerContent-2L12VI:after, .theme-dark .divider-3gKybi.dividerRed-MKoLlr .dividerContent-2L12VI:before {
    border-color: var(--important-notification-l);
    
}

/* fixed bg */
.messages-3amgkR,.searchBar-3TnChZ,.scroller-1JbKM,.activityPanel-9icbyU,.container-YkUktl,.scroller-2TZvBN,.scroller-WSmht3,.scroller-2wx7Hm,.bodyInner-245q0L,.contentRegionScroller-2_GT_N,.sidebarRegionScroller-FXiQOh,.container-ZMc96U.themed-Hp1KC_,.friendsTable-133bsv,.friendsTable-133bsv .friendsTableBody-1ZhKif,.scroller-29cQFV,.emptyStateLarge-1nQX5A,.theme-dark .layout-1cQCv2,#bd-pub-button,.customScroller-m1-jZn,.scroller-305q3I,.header-2w6VV8,.inner-ZyuQk0,.theme-dark .footer-1Ip3Sd,.container-1zzFcN,.platform-win .scroller-2TZvBN,.scroller-2qwVWY,.footer-C9oLp9,.noResults-1ceiMB, .scroller-1Kbkqa,.theme-dark .messagesPopout-24nkyi.markup-eYLPri code.inline,.barButtonBase-3UKlW2,.uploadModal-2ifh8j,.uploadModal-2ifh8j .footer-3mqk7D,.emojiPicker-3m1S-j,.listeningAlong-6YvYsc,.bda-dark .emojiPicker-3m1S-j .category-2U57w6,.emptyResultsWrap-3Kv0LQ,.searchHeader-1l-wpR,.measurement-36xDqs,.panel-2ZFCRb,.modalBody-LuOFny,.perksModalContentWrapper-2HU6uL,.scroller-5bBood {
     background: #0a0a0a!important;
    
}
.markup-eYLPri pre code {
     box-shadow: 0 0 0 1px #3c3c3c,0 0 0 2px #282828,0 0 0 3px #3c3c3c,0 0 0 4px #0a0a0a;
     border-radius: 0px!important;
     transition: all ease-in 0.1s;
     background: var(--mention-color)!important;
    
}
.contextMenu-HLZMGh {
     box-shadow: 0 0 0 1px #3c3c3c,0 0 0 4px #282828,0 0 0 5px #3c3c3c,0 0 0 6px #0a0a0a!important;
     border-top: solid 2px var(--channels-text-selected)!important;
     border-radius: 0px!important;
     background: var(--mention-color)!important;
     
}

/* bda-emojipicker */
.bda-dark .emojiPicker-3m1S-j {
     box-shadow: 0 0 0 1px #3c3c3c,0 0 0 4px #282828,0 0 0 5px #3c3c3c,0 0 0 6px #0a0a0a!important;
     border-radius: 0px!important;
     background: var(--mention-color)!important;
     
}
.bda-dark .emojiPicker-3m1S-j:before {
     content:'';
     position:absolute;
     width:100%;
     height:2px;
     background:linear-gradient(to right,#37b1da 0,#c948cd 50%,#cce335 100%);
     top:0px;
     left:-1px;
    
}
.bda-dark .emojiPicker-3m1S-j .category-2U57w6 {
     background-color: var(--mention-color)!important;
    
}

/* blocked */
.wrapper-2SplAX {
     box-shadow: 0 0 0 1px #3c3c3c,0 0 0 4px #282828,0 0 0 5px #3c3c3c,0 0 0 6px #0a0a0a!important;
     border-radius: 0px!important;
     background: var(--mention-color)!important;
     
}
.wrapper-2SplAX:before {
     content:'';
     position:absolute;
     width:100%;
     height:2px;
     background:linear-gradient(to right,#37b1da 0,#c948cd 50%,#cce335 100%);
     top:10px;
     left:-1px;
     
}

/* bottag */
.botTagRegular-2HEhHi {
     background-color: var(--primary-color);
    
}
.botTag-7aX5WZ {
     font-size: 12px!important;
    
}

/* add role gui */
.container-1S70rv {
     box-shadow: 0 0 0 1px #3c3c3c,0 0 0 4px #282828,0 0 0 5px #3c3c3c,0 0 0 6px #0a0a0a!important;
     border-radius: 0px!important;
     background: var(--mention-color)!important;
     
}
.container-1S70rv .headerText-27z-EV {
     font-size: 10px!important;
    
}
.theme-dark .row-1Ib2uD {
     background-color: var(--mention-color);
    
}
.container-1S70rv:before {
     content:'';
     position:absolute;
     width:100%;
     height:2px;
     background:linear-gradient(to right,#37b1da 0,#c948cd 50%,#cce335 100%);
     top:1px;
     left:-1px;
    
}

/* view profile text */
.avatarHintInner-Dco91E {
     font-size: 12px!important;
     font-weight: normal!important;
     text-transform: none!important;
    
}

/* gif selector */
.autocomplete-3NRXG8 {
     box-shadow: 0 0 0 1px #3c3c3c,0 0 0 4px #282828,0 0 0 5px #3c3c3c,0 0 0 6px #0a0a0a!important;
     border-radius: 0px!important;
     background: var(--mention-color)!important;
     
}
.autocomplete-3NRXG8:before {
     content:'';
     position:absolute;
     width:100%;
     height:2px;
     background:linear-gradient(to right,#37b1da 0,#c948cd 50%,#cce335 100%);
     top:0px;
     left:-1px;
     
}

/* messages popout */
 .theme-dark .messagesPopoutWrap-1MQ1bW {
     box-shadow: 0 0 0 1px #3c3c3c,0 0 0 4px #282828,0 0 0 5px #3c3c3c,0 0 0 6px #0a0a0a!important;
     border-radius: 0px!important;
     background: var(--mention-color)!important;
     
}
.theme-dark .messagesPopoutWrap-1MQ1bW:before {
     content:'';
     position:absolute;
     width:100%;
     height:2px;
     background:linear-gradient(to right,#37b1da 0,#c948cd 50%,#cce335 100%);
     top:0px;
     left:-1px;
     
}
.themedPopout-1TrfdI .header-2Kf7Yu{
     z-index: 0!important;
    
}

/* connection status */
.container-1ILvLB {
     box-shadow: 0 0 0 1px #3c3c3c,0 0 0 4px #282828,0 0 0 5px #3c3c3c,0 0 0 6px #0a0a0a!important;
     border-radius: 0px!important;
     background: var(--mention-color)!important;
     
}
.theme-dark .container-1ILvLB .header-2C89wJ,.theme-dark .container-1ILvLB section {
     background: var(--mention-color)!important;
    
}
.theme-dark .container-1ILvLB .header-2C89wJ:before {
     content:'';
     position:absolute;
     width:100%;
     height:2px;
     background:linear-gradient(to right,#37b1da 0,#c948cd 50%,#cce335 100%);
     top:0px;
     left:-1px;
     
}

/* ----------- */
.contextMenu-HLZMGh:before {
     content:'';
     position:absolute;
     width:101%;
     height:2px;
     background:linear-gradient(to right,#37b1da 0,#c948cd 50%,#cce335 100%);
     top:-2px;
     left:-1px;
    
}

/* random button */
.selectorButtonSelected-336oUc {
     background-color: var(--primary-color)!important;
    
}
.container-3cGP6G {
     box-shadow: 0 0 0 1px #3c3c3c,0 0 0 4px #282828,0 0 0 5px #3c3c3c,0 0 0 6px #0a0a0a!important;
     border-radius: 0px!important;
     background: var(--mention-color)!important;
    
}
.container-3cGP6G:before {
     content:'';
     position:absolute;
     width:101%;
     height:2px;
     background:linear-gradient(to right,#37b1da 0,#c948cd 50%,#cce335 100%);
     top:-2px;
     left:-1px;
     
}
.barButtonBase-3UKlW2 {
     background-color: var(--mention-color)!important;
     box-shadow: 0 0 0 1px #3c3c3c,0 0 0 4px #282828,0 0 0 5px #3c3c3c,0 0 0 6px #0a0a0a!important;
     border-radius: 0px!important;
     opacity: 1!important;
     color: whitesmoke!important;
    
}
.container-36u7Lw {
     font-size: 12px!important;
    
}
.role-2irmRk {
     border-radius: 0px!important;
    
}
.roleName-2ZJJYR {
     font-size: 12px!important;
    
}
.userSettingsAccount-2eMFVR div:nth-child(2)>div:nth-child(2)>.viewBody-2Qz-jg:hover {
    \tfilter: blur(0)
}
.userSettingsAccount-2eMFVR div:nth-child(2)>div:nth-child(2)>.viewBody-2Qz-jg {
    \tfilter: blur(5px);
    \ttransition: 250ms filter ease-in-out
}
.content-3at_AU {
     margin: 1px;
    
}
.modeSelected-1zApJ_ .content-3at_AU, .modeSelected-1zApJ_:hover .content-3at_AU {
     border-radius: 0px!important;
     background: var(--mention-color)!important;
     
}
.theme-dark .attachment-33OFj0 {
     box-shadow: 0 0 0 1px #3c3c3c,0 0 0 2px #282828,0 0 0 3px #3c3c3c,0 0 0 4px #0a0a0a;
     border-radius: 0px!important;
     background: var(--mention-color)!important;
    
}
.weightSemiBold-1WYsXZ {
     font-weight: 400!important;
     font-size: 14px!important;
    
}
.userPopout-3XzG_A.da-userPopout {
     box-shadow: 0 0 0 1px #3c3c3c,0 0 0 4px #282828,0 0 0 5px #3c3c3c,0 0 0 6px #0a0a0a!important;
     border-radius: 0px!important;
     background: var(--mention-color)!important;
     
}
.userPopout-3XzG_A.da-userPopout:before {
     content:'';
     position:absolute;
     width:100%;
     height:2px;
     background:linear-gradient(to right,#37b1da 0,#c948cd 50%,#cce335 100%);
     top:0px;
     left:0px;
    
}
.activity-11LB_k {
     background-color: var(--channels-selected)!important;
    
}
.menu-Sp6bN1 {
     box-shadow: 0 0 0 1px #3c3c3c,0 0 0 4px #282828,0 0 0 5px #3c3c3c,0 0 0 6px #0a0a0a!important;
     border-radius: 0px!important;
     background: var(--mention-color)!important;
     
}
.separator-2zcjq8 {
     width: auto!important;
    
}
.clickable-2ap7je .header-2o-2hj:hover, .selected-WP3kCM .header-2o-2hj {
     background-color: #0a0a0a!important;
    
}
.uploadModal-2ifh8j .inner-3nWsbo {
     border-color: var(--primary-color)!important;
    
}
.lookInverted-2D7oAl.colorBrand-3pXr91 {
     background-color: var(--primary-color)!important;
     color: whitesmoke!important;
    
}
.markup-eYLPri code.inline {
     padding: 0em!important;
     background-color: #0a0a0a!important;
    
}
.container-YkUktl {
     margin-bottom: 0px!important;
    
}
.wrapper-3kah-n.selected-1Drb7Z .childWrapper-1j_1ub, .wrapper-3kah-n .childWrapper-1j_1ub {
     background-color: var(--channels-color)!important;
     color: var(--primary-color)!important;
    
}
.selected-1-Z6gm .layout-1qmrhw {
     transition: text ease-in 0.1s;
     border-radius: 0px;
     background: var(--mention-color)!important;
     color: white;
    
}
.metadata-3WGS0M {
     color: #cbcbcb!important;
    
}
.modeConnected-2IEL4z .name-3_Dsmg, .modeConnected-2IEL4z:hover .name-3_Dsmg, .modeSelected-1zApJ_ .name-3_Dsmg {
     color: white;
    
}
.circleIconButton-jET_ig {
     color: #a0db15!important;
     background: #0a0a0a!important;
    
}
.layout-1qmrhw {
     transition: all ease-in 0.1s;
    
}
.theme-dark .placeholderWrapper-3FaLtZ {
     background: var(--mention-color)!important;
    
}
.mention {
     background: var(--chat-color)!important;
     color: var(--link-color)!important;
     text-shadow: 0 0 5px #a0db15!important;
     border-radius: 2px;
    
}
.lookFilled-1Gx00P.colorBrand-3pXr91 {
     background-color: #75a00d!important;
    
}
.name-3YKhmS, .tierTooltipTitle-1EIbL_ {
     color: whitesmoke!important;
    
}
.lookFilled-1Gx00P.colorGreen-29iAKY {
     background-color: var(--channels-text-selected)!important;
    
}
.children-3xh0VB:after {
     display: none!important;
    
}
.markup-eYLPri a {
     color: var(--link-color)!important;
     text-shadow: 0 0 5px var(--link-color)!important;
    
}
.membersGroup-2eiWxl {
     height: 45px!important;
    
}
.anchor-1MIwyf {
     color: #a0db15;
    
}
.cancelButton-oOSTov, .downloadButton-2HLFWN {
     color: #a0db15!important;
    
}
.expandedFolderBackground-2sPsd- {
     background-color: var(--dropdown-color);
    
}
.edited-DL9ECl {
     margin-left: 0.2px;
     margin-top: 0.03em;
    
}
.mediaBarGrabber-FvJKJg, .mediaBarProgress-1xaPtl, .mediaBarProgress-1xaPtl:after, .mediaBarProgress-1xaPtl:before {
     background-color: var(--link-color)!important;
    
}
.emptyResultsWrap-3Kv0LQ {
     color: #0a0a0a!important;
    
}
.theme-dark .messagesPopout-24nkyi,.theme-dark .jumpButton-3DTcS_,.theme-dark .messageGroupWrapper-o-Zw7G:hover .actionButtons-1sUUug {
     background-color: #0a0a0a!important;
     box-shadow: none;
    
}
.theme-dark .option-1l2vXE {
     background-color: #111;
    
}
.theme-dark .consent-1AQ-th, .theme-light .consent-1AQ-th {
     background-color: var(--link-color);
    
}
.blockquoteDivider-363utW {
     background-color: var(--link-color);
    
}
.base-3IDx3L {
     font-size: 10px!important;
    
}
.numberBadge-37OJ3S.base-3IDx3L.da-numberBadge {
     background-color: var(--link-color)!important;
     width: 20px;
    
}
.lowerBadge-3WTshO.da-lowerBadge {
     transform: translate(1px, 0px)!important;
    
}

/* LiveIcon. */
.live-2o_S8y {
     background-color: var(--primary-color)!important;
    
}

/* Chat(Input)box. */
.inner-zqa7da:before {
     content:'';
     position:absolute;
     width: 99.76%;
     height:2px;
     background:linear-gradient(to right,#37b1da 0,#c948cd 50%,#cce335 100%);
     top:1.8px;
     left:1px;
    
}
.button-2vd_v_,.button-2fCJ0o {
     padding: 4px!important;
     margin: 10px;
    
}

/*Update stuff*/
.form-2fGMdU:before{
     display:none;
    
}
 
/* Discord Message box */
:root {
     --color-brand-lighter: #a2e427;
    
}
.input-2z42oC,.scrollableContainer-15eg7h {
     background-color: #141414;
     transition: background-color 0.2s ease, border-color 0.2s ease;
     border: 1px solid transparent;
     outline: none;
    
}
.input-2z42oC:hover,.scrollableContainer-15eg7h:hover {
     border-color: #96c83c!important;
    ;
     background-color: #181818!important;
    ;
     box-shadow: 0px 0px 3px 1px #96c83c;
    
}
.input-2z42oC:focus-within,.scrollableContainer-15eg7h:focus-within {
     background-color: #1f1f1f!important;
    ;
     border-color: var(--color-brand-lighter)!important;
    
}
.scrollableContainer-15eg7h {
     border: 1px solid transparent;
     border-radius: 5px;
    
}

/*Change selected channel side color*/
.containerDefault-YUSmu3.selected-2TbFuo {
     border-left: 1px solid #9fca2b;
     box-shadow: 0px 0px 3px 1px #96c83c!important;
    
}

/* Pings */
.numberBadge-37OJ3S {
     animation: animatedPing 1.3s infinite ease-in-out;
    
}
@keyframes animatedPing {
     0% {
         transform: rotate(-12deg);
         
    }
     50% {
         transform: rotate(12deg) scale(1.2);
         
    }
     100% {
         transform: rotate(-10deg);
         
    }
    
}

/* Hover Channels animated */
.mainContent-20q_Hp:hover {
     animation: UserModalButtons 0.5s normal ease;
}
.mainContent-20q_Hp .noWrap-hBpHBz {
    width: 100px;
    opacity: 1;
}
.mainContent-20q_Hp {
    transition: 0.2s;
}
.mainContent-20q_Hp:hover {
    transition: 0.2;
}
@keyframes UserModalButtons {
     0% {
         transform: translateY(0px);
         
    }
     45% {
         transform: translateY(-5px);
         
    }
     90% {
         transform: translateY(0px);
         
    }
    
}
#app-mount .privateChannels-oVe7HL .searchBar-3TnChZ {
     position: absolute;
     bottom: 20px;
     right: 5px;
     height: 40px;
     width: 42px;
     border: none;
     border-radius: 40px;
     background: linear-gradient(to bottom right, var(--main-color, #323232), var(--hover-color, #323232));
     box-shadow: 2px 10px 10px var(--shadow, rgba(75, 75, 75, 0.399)) !important;
     overflow: hidden;
     cursor: pointer;
     transition: all .4s ease-in-out;
     pointer-events: all;
     padding: 0;
    
}
#app-mount .privateChannels-oVe7HL .searchBar-3TnChZ .searchBarComponent-3N7dCG {
     background-color: transparent !important;
    
}
.privateChannels-oVe7HL .searchBar-3TnChZ .inner-1NoIT5 {
     height: 100%;
     width: 100%;
    
}
#app-mount .privateChannels-oVe7HL .searchBar-3TnChZ .searchBarComponent-3N7dCG::after {
     content: '';
     position: absolute;
     height: 100%;
     width: 30px;
     bottom: 1px;
     right: 5px;
     background-color: #9fca2b!important;
     -webkit-mask: url('data:image/svg+xml,%3Csvg xmlns=\"http://www.w3.org/2000/svg\" height=\"24px\" viewBox=\"0 0 24 24\" width=\"24px\" fill=\"%23000000\"%3E%3Cpath d=\"M0 0h24v24H0z\" fill=\"none\"/%3E%3Cpath d=\"M15.5 14h-.79l-.28-.27C15.41 12.59 16 11.11 16 9.5 16 5.91 13.09 3 9.5 3S3 5.91 3 9.5 5.91 16 9.5 16c1.61 0 3.09-.59 4.23-1.57l.27.28v.79l5 4.99L20.49 19l-4.99-5zm-6 0C7.01 14 5 11.99 5 9.5S7.01 5 9.5 5 14 7.01 14 9.5 11.99 14 9.5 14z\"/%3E%3C/svg%3E') center/cover no-repeat;
    
}
#app-mount .privateChannels-oVe7HL .searchBar-3TnChZ .searchBarComponent-3N7dCG::before {
     content: 'Search Direct Messages';
     position: absolute;
     top: 50%;
     transform: translateY(-25%);
     width: 180px;
     bottom: 0;
     right: 0.3vw;
     color: #9fca2b;
}
@import url(https://mwittrien.github.io/BetterDiscordAddons/Themes/_res/SettingsIcons.css);
/*-------------------------------*/
/* gamesense theme by Xyhlo#2379 */
/* 	     version:            */
/*	       1.3	         */
/*-------------------------------*/

:root{
    --title-gradient:linear-gradient(to right,#37b1da ,#c948cd ,#cce335, #37b1da);
    --primary-color:#75a00d;
    --background-secondary: #0a0a0a;
    --outline-color:#0a0a0a;
    --outline-lightcolor:#303030;
    --app-color:#0b0b0b;
    --channels-color:#111;
    --channeltextarea-background: #000;
    --channels-darker:#0c0c0c;
    --channels-selected:#191919;
    --channels-text-selected:#9fca2b;
    --chat-color:#0b0b0b;
    --mention-color:#1f1f1f;
    --scrollbar-bg:#202020;
    --scrollbar-thumb:#414141;
    --text-input:#191919;
    --dropdown-color:#232323;
    --link-color:#96c83c;
    --channel-radius:5px;
    --text-color:#cbcbcb;
    --text-darker:#b0b0b0;
    --font:'Verdana',Helvetica,Arial,sans-serif;
    --important-notification-l:#f84747;
    --important-notification:#d12020;
    
}



.search-2oPWTC:not(.open-6_Y_aH) .searchBar-3dMhjb { width: 27px; transition: 0.25s; background-color: transparent;}
.search-2oPWTC:not(.open-6_Y_aH):hover .searchBar-3dMhjb { width: 240px; background-color: var(--background-tertiary);}
.search-2oPWTC:not(.open-6_Y_aH) .iconContainer-O4O2CN { transform: scale(1.3); transition: 0.25s;}
.search-2oPWTC:not(.open-6_Y_aH):hover .iconContainer-O4O2CN { transform: scale(1);}
.icon-3cZ1F_ { color: var(--text-normal)}



.scrollableContainer-2NUZem { padding-right: 11px ; }

.typeWindows-1za-n7 {
    animation: rgbTop 3s infinite linear;
}
@keyframes rgbTop {
    0% {
        background-position: 1920px;
    }
    100% {
        background-position: 0px;
    }
}

.scrollableContainer-2NUZem::-webkit-scrollbar {
    display: none;
}

[aria-label="Inbox"],
[href="https://support.discord.com"] {
  display: none;
}
.avatarHintInner-1TvA8u {
    font-size: 8px !important;
}

/* Change ping badge color */
.numberBadge-2s8kKX {background-color: #6e9601 !important}

/*Remove Stage Discovery Tab*/
#private-channels [href="/discovery"] {display: none}

/*Remove Library Tab*/
#private-channels [href="/library"] {display: none}

/*Remove Nitro Tab*/
#private-channels [href="/store"] {display: none}

/*Unread channels rainbow wave*/
.wrapper-2jXpOf.modeUnread-1qO3K1 .name-23GUGE {
    background-image: linear-gradient(to left,rgb(51, 255, 0), rgb(255, 230, 0), red, rgb(234, 0, 255), rgb(0, 140, 255), rgb(51, 255, 0));
    animation: gradient-border 3s linear infinite;
    background-size: 400% 100%;
    color: transparent !important;
    -webkit-background-clip: text;
    position: relative;
    z-index: 1;
}
@keyframes gradient-border {
    0%, 200% {
        background-position: 0 0;
    }

    99.999999999999999% {
        background-position: 130% 0;
    }
}
/*Remove gift nitro and stickers button*/
.button-38aScr[aria-label="Send a gift"] {
    display:none;
    }
    .button-38aScr[aria-label="Open sticker picker"] {
    display:none;
    }
    
.expandedFolderBackground-1cujaW,.expandedFolderIconWrapper-Huv7r{/*couleur fichier ouvert*/
    background-color:#0a0a0a!important;
}
.members-1998pB, 
.members-1998pB > .content-3YMskv {
    background: #0a0a0a !important;
}
#app-mount .wrapper-1Rf91z {
    background-color: #0a0a0a !important;
}
/*Change selected channel side color*/
.containerDefault--pIXnN.selected-3LIHYU {
    border-left: 6px solid #9fca2b;
}

#app-mount .container-3auIfb, #app-mount .bd-switch-body {
    width: 20px;
    height: 20px;
    background: transparent !important;
  }
  #app-mount .container-3auIfb .slider-TkfMQL, #app-mount .bd-switch-body .bd-switch-slider {
    left: -6px !important;
  }
  #app-mount .container-3auIfb .slider-TkfMQL > rect, #app-mount .bd-switch-body .bd-switch-slider rect {
    height: 20px !important;
    width: 20px !important;
    x: 4px !important;
    y: 0px !important;
    rx: 5;
    fill: var(--background-tertiary);
  }

.wrapper-3NnKdC::before { /*Guild wrapper background*/
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    bottom: 0;
    right: 0;
    background: #0a0a0a;
    background-size: cover;
}
.tree-2wKJdG, .scroller-1Bvpku,.wrapper-3NnKdC { /*Guild subcontainer*/
    background: transparent;
}
/*connections look cooler*/
.connectedAccount-2Jb-Z0:active{
    border-width: 1.2px 1.2px 1.2px 1.2px;
    transform: translateY(1px);
    transition: 0.1s;
}
.connectedAccount-2Jb-Z0
{
    border: solid #151b27;
    border-width: 1.2px 1.2px 3px 1.2px;
    border-radius: 4px;
    transition: 0.1s;
}

.scrollableContainer-2NUZem {
    border: 1px solid #9fca2b;
  }
  svg.homeIcon-FuNwkv{
    color:transparent;
}

/* Custom home icon */
#app-mount .listItemWrapper-KhRmzM .childWrapper-anI2G9 {
    background: url('https://i.ytimg.com/vi/meqVOjIO45A/maxresdefault.jpg') center/cover no-repeat;
}
.homeIcon-FuNwkv {
    display: none;
}
*{
    font-size: 15px!important;
    font-family:var(--font)!important
}

strong{
    font-weight:normal
}

a{
    color:var(--link-color)
}

body{

    font-family:var(--font)!important;
    background-color:var(--app-color)
    
}

input,textarea{
    font-family:var(--font)!important
}

.wrapper-1Rf91z{
	background-color:#191919;
}

.appMount-3lHmkl{
    left:6px;
    top:6px;
    height:calc(100vh - 12px);
    width:calc(100vw - 12px);
    box-shadow:0 0 0 1px #3c3c3c,0 0 0 4px #282828,0 0 0 5px #3c3c3c,0 0 0 6px #0a0a0a;
    background-color:var(--channels-color)
}

.typeWindows-1za-n7{
    height:25px;
    background:var(--primary-color);
    margin-top:1px!important;
    margin-left:1px;
    margin-right:1px;
    background:var(--title-gradient);
    box-shadow:inset 0 -23px 0 0 var(--app-color),inset 0 -24px 0 0 rgba(0,0,0,0.5);
    opacity:1.0;
    z-index:50;
    border-bottom:1px solid var(--outline-lightcolor)
}

*/.typeWindows-1za-n7:hover{
	height:20px;
	transition: all .6s;
	opacity: 1;
}*/

.winButton-iRh8-Z{
    top:2px!important
}
.word mark-2iDDfm{
    opacity:1.0;
    font-family:'Raleway';
}
.wordmark-2iDDfm::before{
    content:'game';
    font-size:14px;
    z-index:1000;
    position:fixed;
    display:inline-block;
    color:var(--text-color);
    height:auto;
    top:12px;
    left:12px;
    background-color:transparent;
}
.mention-1f5kbO {
    background-color: var(--primary-color)!important;
}
.wordmark-2iDDfm::after{
    content:'sense';
    font-size:14px;
    z-index:1000;
    position:fixed;
    display:inline-block;
    color:var(--primary-color);
    height:auto;
    top:12px;
    left:52px;
    background-color:transparent;
}

.winButtonClose-1HsbF-{
    height:33px;
}
.winButtonClose-1HsbF-:hover{
    background-color: transparent;
}
.winButtonMinMax-PBQ2gm{
	height:33px;
}
.winButtonMinMax-PBQ2gm:hover{
    background-color: transparent;
}
.wordmark-2iDDfm svg{
    display:none;
}
.theme-dark .guildsWrapper{
    background:var(--channels-darker);
    box-shadow:inset -1px 0 0 0 #303030,inset -2px 0 0 0 #000
}
.guildsWrapper .guildsAdd-21_Id{
    border-radius:0;
    background:var(--chat-color);
    border:1px dashed var(--outline-lightcolor);
    color:var(--outline-lightcolor)
}
.guildsWrapper-1Rf91z .guildsAdd-21_Id:hover{
    color:var(--text-color);
    border-color:var(--text-color)
}
.guildsWrapper-1Rf91z .guildsAdd-21_Id-inner{
    top:-2px
}
.guildsWrapper-1Rf91z .guilds-1q_RqH .guilds-1q_RqH+.guilds-1q_RqH{
    margin-bottom:25px;
    margin-top:25px
}
.guildInner-3DSoA4{
    border-radius:0!important
}
.guildsWrapper-1Rf91z .guilds-1q_RqH .guild-1EfMGQ+.guild-1EfMGQ{
    margin-top:25px
}
.guildsWrapper-1Rf91z .guilds-1q_RqH .friendsOnline-_wi_fM{
    padding-bottom:10px;
    font-size:9px
}
.guildsWrapper-1Rf91z .guilds-1q_RqH .guild-1EfMGQ.selected-ML3OIq:before{
    box-shadow:0 1px 0 0 #303030,-1px 2px 0 0 #000,0 -1px 0 0 #303030,-1px -2px 0 0 #000;
    background:var(--channels-color);
    border-radius:0;
    height:70px;
    margin-top:-35px;
    width:75px;
    -webkit-transition:none;
    transition:none
}
.guildsWrapper-1Rf91z .guilds-1q_RqH .guild-1EfMGQ .guildInner-3DSoA4{
    background:var(--chat-color)!important
}
.guildsWrapper-1Rf91z .guilds-1q_RqH .guild-1EfMGQ.selected-ML3OIq .guildInner-3DSoA4 a{
    background-color:var(--primary-color)!important;
    transition:all .3s ease
}
.guildsWrapper-1Rf91z .guilds-1q_RqH .guild-1EfMGQ.selected-ML3OIq .guildInner-3DSoA4{
    background-color:var(--primary-color)!important;
    transition:all .3s ease
}
.guildInner-3DSoA4{
    background-color:var(--primary-color);
    border-radius:var(--channel-radius)!important;
    transition:all .3s ease
}
.guildInner-3DSoA4:hover{
    background-color:var(--primary-color)!important;
    transition:all .3s ease
}
.guild-1EfMGQ.active .guildInner-3DSoA4{
    background:var(--primary-color)!important
}
.guildsWrapper-1Rf91z .guildseparator-1X4GQ1{
    display:none
}
.guildsAdd-21_IdK {
	border-radius: 10%;
}
.avatar-large,.avatar-profile,.avatar-small,.avatar-xlarge,.avatar-xsmall,.avatar-xxlarge{
    border-radius:var(--channel-radius)!important
}
.avatarHint-1qgaV3{
	border-radius:var(--channel-radius)!important
}
.container-PNkimc{
    background:none!important
}
.base-3dtUhz{
    border-radius:0!important
}
.header-2o-2hj{
    background:var(--channels-darker);
    box-shadow:none!important;
    border-bottom:1px solid var(--outline-lightcolor)
}
.header-2o-2hj:hover{
    background:var(--channels-selected)
}
.container-1UB9sr{
    border-top:1px solid var(--outline-lightcolor);
    border-bottom:0;
    background:var(--chat-color);
    font-size:11px;
    padding:5px 10px 5px 10px
}
.channels-Ie2l6A.vertical-V37hAW.flex-1O1GKY.directionColumn-35P_nr {
    background:var(--channels-color);
    border-right:1px solid var(--outline-lightcolor)
}
.name-3M0b8v{
    font-size:13px;
    font-weight:700
}
.contentSelectedText-3wUhMi{
    background:var(--channels-selected)
}

.nameSelectedText-sp_EUw,.nameSelectedVoice-1qSph5,svg.colorSelectedText-1y4Wvs.icon-sxakjD,svg.colorSelectedVoice-Xcb_9R.icon-sxakjD{
    color:var(--channels-text-selected)!important;
    opacity:1
}


.theme-dark .member-3W1lQa:hover .content-OzHfo4, .theme-dark .member-3W1lQa.popout-open .content-OzHfo4, .theme-dark .member-3W1lQa.popout-open:hover .content-OzHfo4 {
	background:var(--channels-selected)
}

.contentHoveredText-2D9B-x,.contentHoveredVoice-3p_NEO,.contentHoveredVoice-3p_NEO:active,.contentSelectedVoice-1WDIBM:active{
    background:none!important
}
.container-2Thooq{
    background:var(--channels-darker);
    border-top:1px solid var(--outline-lightcolor)
}
.popout{
    background:var(--dropdown-color)!important;
    border:solid 1px var(--outline-color)!important;
    border-radius:1px
}
.small-popout-box{
    background:var(--dropdown-color)!important;
    border:solid 1px var(--outline-color)!important;
    border-radius:1px
}

.theme-dark .messagesPopoutWrap-1MQ1bW .footer-1kmXd4 {
    background: var(--channels-darker)!important;
}
.theme-dark .messagesPopoutWrap-1MQ1bW {
    border-radius: 1px;
    background: var(--channels-color)!important;
    box-shadow: 0 0 0 1px #323232,0 0 0 2px #0a0a0a!important;
}

.theme-dark .messagesPopoutWrap-1MQ1bW .header-ykumBX {
    -webkit-box-shadow: 0 2px 3px 0 rgba(0,0,0,20%);
    background-color: #35393e;
    box-shadow: 0 2px 3px 0 rgba(0,0,0,.2);
    background: var(--channels-darker)!important;
}

.option-popout .btn-item,.option-popout .btn-item:hover{
    color:var(--text-color)
}
.contextMenu-HLZMGh{
    background:var(--dropdown-color)!important;
    border:solid 1px var(--outline-color)!important;
    border-radius:1px;
    box-shadow:none!important
}
.item-1Yvehc{
    font-size:11px!important
}
.item-1Yvehc:hover{
    background:var(--outline-lightcolor)!important;
    border-radius:0
}
.itemSubMenu-1vN_Yn{
    background-color:var(--dropdown-color)!important
}
.menu-Sp6bN1{
    border-radius:1px;
	background:var(--chat-color)!important;
	box-shadow:0 0 0 1px #323232,0 0 0 2px #0a0a0a!important;
}
.item-1GzJrl{
    color:var(--text-color);
    font-size:11px!important
}
.item-1GzJrl:hover{
    border-radius:0!important;
    color:var(--text-color);
    background:var(--outline-lightcolor)!important
}
.separator-2zcjq8{
    border-color:var(--outline-lightcolor)!important;
    width:100%
}
.title-3qD0b-,.titleCall-_b9o8P{
    background:var(--channels-darker)!important;
    box-shadow:inset 0 -1px 0 var(--outline-lightcolor)!important
}
.channelName-3stJzi{
    font-size:13px;
    color:var(--text-color)!important
}
.channelName-3stJzi svg{
    width:14px;
    color:var(--text-color)
}
.channelIcon-MsmKOO{
    top:4px
}
.topic-2QX7LI{
    font-size:11px
}
.messagesWrapper-3lZDfY {
    background:none!important
}
.chat-3bRxxu>.content-yTz4x3{
    background:var(--chat-color)!important
}
.embedPill-1Zntps{
    background:var(--primary-color)!important
}
.embedInner-1-fpTo{
    background:var(--channels-darker)!important;
    border-radius:1px!important;
    border-color:var(--outline-lightcolor)!important
}
.message-group{
    padding:15px 0
}
.message-group h2 strong{
    font-size:13px
}
.timestampCozy-2hLAPV{
    font-size:9px
}
.markup-2BOw-j{
    font-size:11px;
    line-height:1.4em
}
.markup-2BOw-j pre{
    border-radius:1px!important;
    border:none!important;
    box-shadow:0 0 0 1px #323232,0 0 0 2px #101010!important
}
.markup-2BOw-j pre code{
    font-size:13px;
    background:var(--dropdown-color)!important
}
.hljs-section{
    color:var(--primary-color)!important
}

.theme-dark .divider-3gKybi.dividerRed-MKoLlr .dividerContent-2L12VI>span {
    background:#113!important
}

.theme-dark .divider-3gKybi.dividerRed-MKoLlr .dividerContent-2L12VI:after, .theme-dark .divider-3gKybi.dividerRed-MKoLlr .dividerContent-2L12VI:before {
background:var(--important-notification)!important;
border-color: transparent !important;

}

.theme-dark .divider-3gKybi span {
	background:0b0b0b!important
}
.imageWrapper-2p5ogY{
    border-radius:3px
}
.chat-3bRxxu form{
    background:none!important;
    box-shadow:none!important
}
.inner-zqa7da{
    border-radius:0!important;
    background:var(--text-input)!important;
    box-shadow:inset 0 0 0 1px #323232,inset 0 0 0 2px #101010
}

.channelTextArea-rNsIhG .inner-zqa7da .textArea-2Spzkt{
    font-size:11px;
    line-height: 1.6rem;
}

.theme-dark .channelTextArea-rNsIhG {
	border-top:none;
}
.innerEnabled-3g80kR .textArea-2Spzkt{
    font-size:11px;
    line-height:.80rem;
    margin:12px 2px 2px 0;
    padding:5px 38px 8px 10px
}
.textAreaEnabled-3vQ5WZ{
    padding:5px 38px 8px 0
}
.typing-2GQL18{
    background:none!important;
    font-size:8px!important;
    padding-left:1px
}
.typing-2GQL18 .ellipsis-19qdx6{
    display:none
}
.scroller-2FKFPG.members-1998pB{
    background:var(--channels-darker)!important;
    border-left:solid 1px var(--outline-lightcolor);
    color:red
}

.image-33JSyf{
	border-radius:var(--channel-radius)!important
}

.mask-3OgeRz{
	-webkit-mask: none;
}
::-webkit-scrollbar-thumb{
    border:none!important;
    border-radius:0!important;
    background:#414141!important
}
::-webkit-scrollbar{
    width:6px!important
}
::-webkit-scrollbar-track-piece{
    border:none!important;
    border-radius:0!important;
    background:#2d2d2d!important
}
.scroller-wrap .scroller::-webkit-scrollbar-thumb{
    border:none!important;
    border-radius:0!important;
    background:#414141!important
}
.scroller-wrap .scroller::-webkit-scrollbar{
    width:6px!important
}
.scrollerWrap-2lJEkd .scroller::-webkit-scrollbar-track-piece{
    border:none!important;
    border-radius:0!important;
    background:#2d2d2d!important
}
.scrollerWrap-2lJEkd.scroller::-webkit-scrollbar-thumb{
    border:none!important;
    border-radius:0!important;
    background:#414141!important
}
.scrollerWrap-2lJEkd .scroller::-webkit-scrollbar{
    width:6px!important
}
.scrollerWrap-2lJEkd .scroller::-webkit-scrollbar-track-piece{
    border:none!important;
    border-radius:0!important;
    background:#2d2d2d!important
}
.tooltip,.tooltip.tooltip-black,.tipsy-inner{
    border-radius:1px!important
}
.bd-blue .tooltip-red,.tooltip.tooltip-red{
    background-color:var(--important-notification)
}
.bd-blue .tooltip-red.tooltip-top:after{
    border-top-color:var(--important-notification)
}
.bd-blue .tooltip-red.tooltip-left:after{
    border-left-color:var(--important-notification)
}
.bd-blue .tooltip-red.tooltip-bottom:after{
    border-bottom-color:var(--important-notification)
}
.bd-blue .tooltip-red.tooltip-right:after,.tooltip.tooltip-red.tooltip-right:after{
    border-right-color:var(--important-notification)
}
.tooltip.tooltip-right:after,.tooltip.tooltip-left:after{
    margin-top:-8px
}
.tooltip.tooltip-brand,.tooltip.tooltip-black,.tipsy-inner{
    background:var(--channels-darker)!important;
    border:solid 1px var(--outline-lightcolor)!important;
    border-radius:1px;
    padding:5px 10px;
    font-size:11px;
    font-weight:400;
    line-height:14px;
    text-align:center
}
.tooltip.tooltip-brand.tooltip-right:after,.tooltip.tooltip-black.tooltip-right:after{
    border-radius:0;
    border-right:8px solid var(--outline-lightcolor)!important;
    border-top:8px solid transparent!important;
    border-bottom:8px solid transparent!important
}
.tooltip.tooltip-brand.tooltip-top:after,.tooltip.tooltip-black.tooltip-top:after,.tipsy-se .tipsy-inner:after{
    border-radius:0;
    border-right:8px solid transparent!important;
    border-top:8px solid var(--outline-lightcolor)!important;
    border-left:8px solid transparent!important
}
.tooltip.tooltip-brand.tooltip-left:after,.tooltip.tooltip-black.tooltip-left:after{
    border-radius:0;
    border-left:8px solid var(--outline-lightcolor)!important;
    border-top:8px solid transparent!important;
    border-bottom:8px solid transparent!important
}
.tooltip.tooltip-brand.tooltip-bottom:after,.tooltip.tooltip-black.tooltip-bottom:after{
    border-radius:0;
    border-right:8px solid transparent!important;
    border-bottom:8px solid var(--outline-lightcolor)!important;
    border-left:8px solid transparent!important
}
.checkbox{
    width:8px;
    height:8px;
    background:#4c4c4c;
    background:linear-gradient(to bottom,#4c4c4c 0,#333 100%);
    border-radius:0!important;
    border:1px solid var(--outline-color)
}
.checkbox .checkbox-inner{
    height:8px;
    width:8px;
    border:0
}
.checkbox .checkbox-inner span{
    border:0;
    border-radius:0;
    background:linear-gradient(to bottom,#4c4c4c 0,#333 100%)
}
.checkbox .checkbox-inner input[type=checkbox]:checked+span{
    background:linear-gradient(to bottom,#9cc728 0,#7aa506 100%);
    transition:5.0
}
.checkbox .checkbox-inner input[type=checkbox]:checked+span:after{
    content:none
}
.checkbox .checkbox-inner+span{
    white-space:nowrap;
    color:var(--text-color);
    font-size:11px
}
.grabber-3mFHz2{
    border-radius:5px!important;
    margin-left:-6px!important
}
.bar-2Qqk5Z{
    background:linear-gradient(to bottom,#343434 0,#444 100%)!important;
    border-radius:0!important;
    border:1px solid var(--outline-color)
}
.barFill-23-gu-{
    background:linear-gradient(to bottom,#99c427 0,#699404 100%)!important
}
.bubble-3we2di{
    background:var(--channels-darker)!important;
    border:solid 1px var(--outline-lightcolor)!important;
    border-radius:1px;
    font-size:10px;
    color:var(--text-color)
}
.bubble-3we2di:before{
    border-top-color:var(--outline-lightcolor)
}
#friends{
    background:var(--channels-darker)!important
}
.friends-table{
    background:var(--chat-color)!important;
    border-top:1px solid var(--outline-lightcolor)
}
.tab-bar-item.tab-bar-item-primary{
    background:linear-gradient(to bottom,#232323 0,#191919 100%)!important;
    border-radius:0!important;
    box-shadow:inset 0 0 0 1px #0a0a0a,inset 0 0 0 2px #323232;
    font-size:11px;
    padding:5px 15px 5px 15px!important;
    color:var(--text-color)!important
}
.tab-bar-item.tab-bar-item-primary:hover{
    background:linear-gradient(to bottom,#282828 0,#1e1e1e 100%)!important
}
.tab-bar-item.tab-bar-item-primary.selected{
    background:linear-gradient(to bottom,#1e1e1e 0,#0f0f0f 100%)!important;
    color:var(--primary-color)!important
}
.tab-bar-item{
    color:var(--text-color)!important
}
.tab-bar-item.selected{
    border-radius:0!important;
    background:var(--outline-lightcolor)!important;
    color:var(--primary-color)!important
}
.tab-bar-item:hover{
    border-radius:0!important;
    background:var(--outline-lightcolor)!important
}
.friends-table .friends-row:hover{
    border-radius:0!important;
    background:var(--outline-lightcolor)!important
}
.friends-table .friends-row .friends-column-actions .friends-action:hover{
    background-color:var(--outline-color)!important
}
.private-channels .channel.selected a,.private-channels .channel a:hover{
    background:var(--outline-lightcolor);
    color:var(--text-color)!important;
    margin-right:10px!important
}
.friend-table-add-wrapper .friend-table-add-header{
    background:var(--channels-darker)!important;
    border-bottom:1px solid var(--outline-lightcolor)!important;
    box-shadow:none!important;
    padding-top:10px
}
.friend-table-add-wrapper h2{
    font-size:12px!important
}
.friend-table-add-wrapper h3{
    font-size:11px!important
}
.friend-table-add-wrapper .friend-table-add-description{
    font-size:11px!important
}
.wrapper-3JPufy{
    padding-right:5px
}
.inner-2Y6JuD{
    border-radius:1px;
    border-color:var(--outline-lightcolor);
    background-color:var(--chat-color)
}
.wrapper-1cBijl{
    border-radius:0!important;
    background:var(--text-input)!important;
    box-shadow:inset 0 0 0 1px #323232,inset 0 0 0 2px #101010
}
.friend-table-suggestions-header{
    padding:20px 30px 16px!important
}
.btn{
    background:var(--primary-color)!important
}
.modal-3HD5ck{
    border-radius:0;
    background:var(--channels-darker)!important;
    box-shadow:inset 0 0 0 1px #0a0a0a,inset 0 0 0 2px #323232!important
}
.h4-AQvcAz{
    font-size:13px;
    color:var(--text-color)!important
}
.primary-jw0I4K{
    font-size:12px!important;
    color:var(--text-color)!important
}
.message-group-blocked{
    border-radius:0!important;
    background:var(--dropdown-color)!important
}
.message-group-blocked .message-group-blocked-btn{
    background:var(--channels-color)!important;
    font-size:11px
}
.mention{
    color:var(--primary-color)!important;
    background:var(--mention-color)!important
}
.popout{
    box-shadow:none!important;
    border:var(--outline-lightcolor)!important
}
.userPopout-3XzG_A{
    border-radius:1px;
    box-shadow:0 0 0 1px #323232,0 0 0 2px #0a0a0a!important
}
.headerPlaying-j0WQBV,.headerNormal-T_seeN{
    background:var(--channels-darker)!important
}
.activity-11LB_k{
    background:var(--primary-color)
}
.body-3iLsc4,.footer-1fjuF6{
    background:var(--channels-color)!important
}
.textRow-19NEd_{
    font-size:13px
}
.quickMessage-2XpSaN{
    border-radius:0!important;
    background:var(--text-input)!important;
    border:0;
    box-shadow:inset 0 0 0 1px #323232,inset 0 0 0 2px #101010;
    font-size:11px
}
.role-2irmRk{
    font-size:10px
}
.note-3kmerW textarea{
    border-radius:0!important;
    background:var(--text-input)!important;
    border:0;
    box-shadow:inset 0 0 0 1px #323232,inset 0 0 0 2px #101010;
    font-size:11px
}
.search-results-wrap{
    background:var(--channels-color)!important;
    border-left:1px solid var(--outline-lightcolor)
}
.search-header{
    box-shadow:none!important;
    background:var(--channels-darker)!important;
    border-bottom:1px solid var(--outline-lightcolor)
}
.search-header .tab.selected{
    color:var(--primary-color)!important;
    border-color:var(--primary-color)!important
}
.search-results-wrap .channel-separator .channel-name{
    background:none!important;
    font-size:13px
}
.search-results-wrap .search-result:before,.search-results-wrap .search-result:after{
    background:none!important
}
.search-results-wrap .search-result .hit{
    background:var(--outline-lightcolor)!important;
    border-radius:1px;
    border:1px solid var(--outline-color)!important;
    box-shadow:none!important
}
.search-popout{
    box-shadow:none!important;
    background:var(--channels-color);
    box-shadow:0 0 0 1px #323232,0 0 0 2px #0a0a0a!important;
    border-radius:0
}
.search-popout .option{
    font-size:13px;
    height:24px
}
.search-popout .option.selected:before{
    height:24px
}
.search-popout .option.selected{
    background:var(--outline-lightcolor)
}
.search-popout .search-option .filter,.option.history .answer{
    color:var(--text-darker)
}
.search-popout .option:after,.search-popout .option.selected:after{
    background:0
}
.search-popout .search-query{
    border-bottom:0
}
.system-message{
    font-size:13px
}
.topSectionNormal-2-vo2m{
    background:var(--channels-darker)!important
}
.body-3ND3kc{
    background:var(--channels-color)!important
}
.tabBar-2MuP6- .tab-bar-item.selected{
    border-color:var(--primary-color)!important;
    background:none!important
}
.tabBar-2MuP6- .tab-bar-item:hover{
    background:none!important
}
.topSectionPlaying-1J5E4n{
    background:var(--channels-darker)
}
.autocomplete-1vrmpx{
    background:var(--channels-darker)!important;
    border:1px solid var(--outline-lightcolor)
}
.selectorSelected-1_M1WV{
    border-radius:1px;
    background:var(--channels-color)!important
}
.buttonBrandInvertedDefault-uUmgsD{
    background:var(--primary-color)!important;
    color:#fff
}
.chat-3bRxxu .newMessagesBar-mujexs{
    background:var(--primary-color)!important
}
.unread-1xRYoj{
    background:var(--primary-color)!important
}
.emojiPicker-3m1S-j{
    background:none!important
}
.emojiPicker-3m1S-j .header-1nkwgG .search-bar{
    background:none!important
}
.emojiPicker-3m1S-j .stickyHeader-1SS0JU{
    background:0
}
.emojiPicker-3m1S-j .category-2U57w6{
    color:var(--primary-color)
}
.search-bar.search-bar-light .search-bar-inner{
    border-radius:0!important;
    background:var(--text-input)!important;
    box-shadow:inset 0 0 0 1px #323232,inset 0 0 0 2px #101010
}
.emojiPicker-3m1S-j .categories-1feg4n .item-16cXuq.selected-39BZ4S{
    border-bottom-color:var(--primary-color)
}
.emojiPicker-3m1S-j .scroller-3vODG7 .emojiItem-109bjA.selected-39BZ4S{
    background-color:var(--dropdown-color)
}
.search-bar input{
    font-size:12px!important
}
.form header{
    color:var(--primary-color)!important
}
.form-deprecated,.form.deprecated{
    background:var(--channels-darker)!important;
    box-shadow:inset 0 0 0 1px var(--outline-lightcolor)
}
.form-deprecated .form-inner,.form.deprecated .form-inner{
    background:none!important
}
.form-deprecated .form-actions,.form.deprecated .form-actions{
    background:none!important;
    border-color:var(--outline-lightcolor)
}
.create-guild-container.deprecated .action{
    background:var(--channels-color);
    border:1px solid var(--outline-lightcolor)
}
.create-guild-container.deprecated .action.join:hover .btn{
    background-color:var(--primary-color)!important
}
.form-deprecated .btn-default,.form.deprecated .btn-default,.form-deprecated .btn-default:hover,.form.deprecated .btn-default:hover{
    background:none!important;
    border-bottom:0;
    color:var(--text-color)!important
}
.create-guild-container.deprecated .join-server h5{
    font-size:14px;
    color:var(--primary-color)
}
.create-guild-container.deprecated p{
    font-size:12px
}
.bd-blue .create-guild-container .join-server .sample-link{
    font-size:13px
}
.guild-form li .control-group input[type=text]{
    padding-left:10px
}
.form.deprecated .control-group input[type=text]{
    border-radius:0!important;
    background:var(--text-input)!important;
    border:0;
    box-shadow:inset 0 0 0 1px #323232,inset 0 0 0 2px #101010;
    color:var(--text-color);
    font-size:12px
}
.form.deprecated .control-group input[type=text]:focus{
    border:0
}
.bd-blue .avatar-uploader-inner{
    background:var(--primary-color)!important
}
.regionSelect-3lf4eE .regionSelectInner-24f4Ce,.regionSelect-3lf4eE:hover .regionSelectInner-24f4Ce,.regionSelect-3lf4eE:hover button{
    border-radius:1px;
    border-color:var(--outline-lightcolor)
}
.regionSelect-3lf4eE button,.regionSelect-3lf4eE:hover button{
    border-radius:1px;
    border-color:var(--outline-lightcolor);
    color:var(--text-color);
    background:var(--channels-color)
}
.regionSelectModal-12e-57{
    background:var(--channels-darker)
}
.regionSelectModal-12e-57 .regionSelectModalOption-2DSIZ3{
    background:var(--channels-color);
    border:1px solid var(--outline-lightcolor)
}
.regionSelectModal-12e-57 .regionSelectModalOption-2DSIZ3:hover{
    border-color:var(--primary-color)
}
.message-group a{
    color:var(--link-color)!important
}
.wrapper-2NJDcI{
    background:#232529
}
.themed-popout{
    background:var(--channels-color)!important;
    border-radius:1px!important;
    border:1px solid var(--outline-lightcolor)!important
}
.themed-popout .header{
    background:var(--channels-darker)!important;
    box-shadow:none!important;
    border-bottom:1px solid var(--outline-lightcolor)
}
.themed-popout .footer{
    background:none!important;
    border-top:1px solid var(--outline-lightcolor)
}
.private-channel-recipients-invite .friend{
    background:var(--channels-color)!important
}
.search-bar .search-bar-inner{
    border-radius:0!important;
    background:var(--text-input)!important;
    box-shadow:inset 0 0 0 1px #323232,inset 0 0 0 2px #101010
}
.private-channel-recipients-invite .footer button{
    background:var(--primary-color)!important
}
.video-1FfuMD{
    background:var(--channels-color);
    border-bottom:1px solid var(--outline-lightcolor)
}
.footer-2yfCgX{
    background:none!important
}
.tiles-2aXG_k{
    background:var(--channels-color)!important
}
.selectorButtonSelected-1j4DmC,.buttonBrandFilled-3Mv0Ra,.buttonBrandFilled-3Mv0Ra:hover,.buttonBrandFilled-3Mv0Ra:active{
    background:var(--primary-color)
}
.imageSelected-4Kl81J{
    border-color:var(--primary-color)
}
.quickswitcher-3JagVE{
    background:var(--channels-darker)!important;
    border-radius:1px;
    border:1px solid var(--outline-lightcolor);
    box-shadow:none
}
.input-2VB9rf{
    border-radius:0!important;
    background:var(--text-input)!important;
    box-shadow:inset 0 0 0 1px #323232,inset 0 0 0 2px #101010!important;
    color:var(--text-color)!important
}
.note-3HfJZ5{
    margin-left:0
}
.note-3kmerW textarea{
    padding-top:6px;
    padding-left:10px
}
.form-deprecated .form-header,.form.deprecated .form-header{
    background:0
}
.wrapper-O5i5-0 .instantInviteModal-3vhcvC .form-header header{
    color:var(--primary-color);
    font-size:14px
}
.wrapper-O5i5-0 .instantInviteModal-3vhcvC .blurb-zsamaY{
    color:var(--text-color);
    font-size:11px
}
.wrapper-O5i5-0 .instantInviteModal-3vhcvC .checkbox .checkbox-inner span{
    border:0
}
.wrapper-O5i5-0 .instantInviteModal-3vhcvC .expireText-34b09Y{
    color:var(--text-color)
}
.cclipboardInputInner-1EXMA3{
    border-radius:0!important;
    background:var(--text-input)!important;
    box-shadow:inset 0 0 0 1px #323232,inset 0 0 0 2px #101010;
    border:none!important
}
.wrapper-O5i5-0 .instantInviteModal-3vhcvC .clipboardInputInner-RLx2hK input{
    background:0;
    font-size:16px;
    color:var(--primary-color)
}
.wrapper-O5i5-0 .instantInviteModal-3vhcvC .copy-3nFbq8{
    background:var(--primary-color);
    border:0;
    font-size:11px
}
.cclipboardInputInner-1EXMA3 button:first-of-type:before{
    background:none!important
}
.wrapper-O5i5-0{
    background:0
}
.Select-control,.Select-control:hover,.Select-control:active{
    border-radius:0!important;
    background:var(--text-input)!important;
    box-shadow:inset 0 0 0 1px #323232,inset 0 0 0 2px #101010;
    border:none!important
}
.has-value.Select--single>.Select-control .Select-value .Select-value-label,.has-value.is-pseudo-focused.Select--single>.Select-control .Select-value .Select-value-label,.has-value.Select--single>.Select-control .Select-value .Select-value-label{
    color:var(--text-color)
}
.wrapper-O5i5-0 .instantInviteModalAdvanced-3qJETM .checkbox .checkbox-inner span{
    border:0
}
.Select-option,.Select-option.is-focused{
    background:none!important;
    color:var(--text-color)!important
}
.Select-menu-outer{
    background:var(--channels-color);
    border:1px solid var(--outline-lightcolor)
}

.titleWrapper-1l0xT9 {
	background:var(--channels-darker);
}

.theme-dark .members-1998pB {
	background:var(--channels-darker);
}

.theme-dark .messageGroupWrapper-o-Zw7G {
	background-color: var(--chat-color);
	border-color: var(--outline-lightcolor);
	border-radius: 0px;
	border-width: 1px;
}

.theme-dark .divider-3gKybi.dividerRed-MKoLlr .dividerContent-2L12VI {
	color: var(--important-notification);
}

.theme-dark .divider-3gKybi.dividerRed-MKoLlr .dividerContent-2L12VI:after, .theme-dark .divider-3gKybi.dividerRed-MKoLlr .dividerContent-2L12VI:before {
	border-color: var(--important-notification-l);
}

/*               fixed bg                   */

.messages-3amgkR,
.searchBar-6Kv8R2,
.scroller-1JbKM,
.activityPanel-28dQGo,
.container-3baos1,
.scroller-2TZvBN,
.scroller-1JbKMe,
.scroller-2wx7Hm,
.bodyInner-245q0L,
.contentRegionScroller-26nc1e,
.sidebarRegionScroller-3MXcoP,
.container-1r6BKw.themed-ANHk51,
.friendsTable-133bsv,
.friendsTable-133bsv .friendsTableBody-1ZhKif,
.scroller-9moviB,
.emptyStateLarge-1nQX5A,
.theme-dark .layout-1cQCv2,
#bd-pub-button,
.customScroller-26gWhv,
.scroller-305q3I,
.header-2tA9Os,
.inner-ZyuQk0,
.theme-dark .footer-3rDWdC,
.container-1giJp5,
.platform-win .scroller-2TZvBN,
.scroller-zPkAnE,
.footer-1eyGBa,
.noResults-ZTbl5V, .scroller-hUf6zQ,
.theme-dark .messagesPopout-24nkyi
.markup-2BOw-j code.inline,
.barButtonBase-3UKlW2,
.uploadModal-2ifh8j,
.uploadModal-2ifh8j .footer-3mqk7D,
.emojiPicker-3m1S-j,
.listeningAlong-30wH70,
.bda-dark .emojiPicker-3m1S-j .category-2U57w6,
.emptyResultsWrap-3Kv0LQ,
.searchHeader-1l-wpR,
.measurement-36xDqs,
.panel-24C3ux,
.modalBody-LuOFny,
.perksModalContentWrapper-2HU6uL,
.scroller-5bBood {
    background: #0a0a0a!important;
}

.markup-2BOw-j pre code {
    box-shadow: 0 0 0 1px #3c3c3c,0 0 0 2px #282828,0 0 0 3px #3c3c3c,0 0 0 4px #0a0a0a;
    border-radius: 0px!important;
    transition: all ease-in 0.1s;
    background: var(--mention-color)!important;
}

.contextMenu-HLZMGh {
    box-shadow: 0 0 0 1px #3c3c3c,0 0 0 4px #282828,0 0 0 5px #3c3c3c,0 0 0 6px #0a0a0a!important;
    border-top: solid 2px var(--channels-text-selected)!important;
    border-radius: 0px!important;
    background: var(--mention-color)!important; 
}

/* bda-emojipicker */

.bda-dark .emojiPicker-3m1S-j {
    box-shadow: 0 0 0 1px #3c3c3c,0 0 0 4px #282828,0 0 0 5px #3c3c3c,0 0 0 6px #0a0a0a!important;
    border-radius: 0px!important;
    background: var(--mention-color)!important;  
}

.bda-dark .emojiPicker-3m1S-j:before {
    content:'';
    position:absolute;
    width:100%;
    height:2px;
    background:linear-gradient(to right,#37b1da 0,#c948cd 50%,#cce335 100%);
    top:0px;
    left:-1px;
}

.bda-dark .emojiPicker-3m1S-j .category-2U57w6 {
    background-color: var(--mention-color)!important;
}

/* blocked */

.wrapper-39oAo3 {
    box-shadow: 0 0 0 1px #3c3c3c,0 0 0 4px #282828,0 0 0 5px #3c3c3c,0 0 0 6px #0a0a0a!important;
    border-radius: 0px!important;
    background: var(--mention-color)!important;   
}

.wrapper-39oAo3:before {
    content:'';
    position:absolute;
    width:100%;
    height:2px;
    background:linear-gradient(to right,#37b1da 0,#c948cd 50%,#cce335 100%);
    top:10px;
    left:-1px; 
}

/* bottag */

.botTagRegular-2HEhHi {
    background-color: var(--primary-color);
}

.botTag-2WPJ74 {
    font-size: 12px!important;
}

/* add role gui */

.container-VSDcQc {
    box-shadow: 0 0 0 1px #3c3c3c,0 0 0 4px #282828,0 0 0 5px #3c3c3c,0 0 0 6px #0a0a0a!important;
    border-radius: 0px!important;
    background: var(--mention-color)!important;   
}

.container-VSDcQc .headerText-3i6A8K {
    font-size: 10px!important;
}

.theme-dark .row-rrHHJU {
    background-color: var(--mention-color);
}

.container-VSDcQc:before {
    content:'';
    position:absolute;
    width:100%;
    height:2px;
    background:linear-gradient(to right,#37b1da 0,#c948cd 50%,#cce335 100%);
    top:1px;
    left:-1px;
}

/* view profile text */

.avatarHintInner-Dco91E {
    font-size: 12px!important;
    font-weight: normal!important;
    text-transform: none!important;
}

/* gif selector */

.autocomplete-1vrmpx {
    box-shadow: 0 0 0 1px #3c3c3c,0 0 0 4px #282828,0 0 0 5px #3c3c3c,0 0 0 6px #0a0a0a!important;
    border-radius: 0px!important;
    background: var(--mention-color)!important;  
}

.autocomplete-1vrmpx:before {
    content:'';
    position:absolute;
    width:100%;
    height:2px;
    background:linear-gradient(to right,#37b1da 0,#c948cd 50%,#cce335 100%);
    top:0px;
    left:-1px; 
}

/* messages popout */ 

.theme-dark .messagesPopoutWrap-1MQ1bW {
    box-shadow: 0 0 0 1px #3c3c3c,0 0 0 4px #282828,0 0 0 5px #3c3c3c,0 0 0 6px #0a0a0a!important;
    border-radius: 0px!important;
    background: var(--mention-color)!important;  
}

.theme-dark .messagesPopoutWrap-1MQ1bW:before {
    content:'';
    position:absolute;
    width:100%;
    height:2px;
    background:linear-gradient(to right,#37b1da 0,#c948cd 50%,#cce335 100%);
    top:0px;
    left:-1px;   
}

.themedPopout-1TrfdI .header-2Kf7Yu{
    z-index: 0!important;
}


/* connection status */

.container-2x5lvQ {
    box-shadow: 0 0 0 1px #3c3c3c,0 0 0 4px #282828,0 0 0 5px #3c3c3c,0 0 0 6px #0a0a0a!important;
    border-radius: 0px!important;
    background: var(--mention-color)!important;  
}

.theme-dark .container-2x5lvQ .header-2C89wJ,
.theme-dark .container-2x5lvQ section {
    background: var(--mention-color)!important;
}

.theme-dark .container-2x5lvQ .header-2C89wJ:before {
    content:'';
    position:absolute;
    width:100%;
    height:2px;
    background:linear-gradient(to right,#37b1da 0,#c948cd 50%,#cce335 100%);
    top:0px;
    left:-1px;   
}

/* ----------- */

.contextMenu-HLZMGh:before {
    content:'';
    position:absolute;
    width:101%;
    height:2px;
    background:linear-gradient(to right,#37b1da 0,#c948cd 50%,#cce335 100%);
    top:-2px;
    left:-1px;
}

/* random button */

.selectorButtonSelected-336oUc {
    background-color: var(--primary-color)!important;
}

.container-3cGP6G {
    box-shadow: 0 0 0 1px #3c3c3c,0 0 0 4px #282828,0 0 0 5px #3c3c3c,0 0 0 6px #0a0a0a!important;
    border-radius: 0px!important;
    background: var(--mention-color)!important;
}

.container-3cGP6G:before {
    content:'';
    position:absolute;
    width:101%;
    height:2px;
    background:linear-gradient(to right,#37b1da 0,#c948cd 50%,#cce335 100%);
    top:-2px;
    left:-1px;  
}

.barButtonBase-3UKlW2 {
    background-color: var(--mention-color)!important;
    box-shadow: 0 0 0 1px #3c3c3c,0 0 0 4px #282828,0 0 0 5px #3c3c3c,0 0 0 6px #0a0a0a!important;
    border-radius: 0px!important;
    opacity: 1!important;
    color: whitesmoke!important;
}

.container-2ax-kl {
    font-size: 12px!important;
}

.role-2irmRk {
    border-radius: 0px!important;
}

.roleName-32vpEy {
    font-size: 12px!important;
}

.userSettingsAccount-2eMFVR div:nth-child(2)>div:nth-child(2)>.viewBody-2Qz-jg:hover {
	filter: blur(0)
}

.userSettingsAccount-2eMFVR div:nth-child(2)>div:nth-child(2)>.viewBody-2Qz-jg {
	filter: blur(5px);
	transition: 250ms filter ease-in-out
}

.content-3at_AU {
    margin: 1px;
}

.modeSelected-1zApJ_ .content-3at_AU, .modeSelected-1zApJ_:hover .content-3at_AU {
    border-radius: 0px!important;
    background: var(--mention-color)!important; 
}

.theme-dark .attachment-33OFj0 {
    box-shadow: 0 0 0 1px #3c3c3c,0 0 0 2px #282828,0 0 0 3px #3c3c3c,0 0 0 4px #0a0a0a;
    border-radius: 0px!important;
    background: var(--mention-color)!important;
}

.weightSemiBold-1WYsXZ {
    font-weight: 400!important;
    font-size: 14px!important;
}

.userPopout-3XzG_A.da-userPopout {
    box-shadow: 0 0 0 1px #3c3c3c,0 0 0 4px #282828,0 0 0 5px #3c3c3c,0 0 0 6px #0a0a0a!important;
    border-radius: 0px!important;
    background: var(--mention-color)!important; 
}

.userPopout-3XzG_A.da-userPopout:before {
    content:'';
    position:absolute;
    width:100%;
    height:2px;
    background:linear-gradient(to right,#37b1da 0,#c948cd 50%,#cce335 100%);
    top:0px;
    left:0px;
}

.activity-11LB_k {
    background-color: var(--channels-selected)!important;
}

.menu-Sp6bN1 {
    box-shadow: 0 0 0 1px #3c3c3c,0 0 0 4px #282828,0 0 0 5px #3c3c3c,0 0 0 6px #0a0a0a!important;
    border-radius: 0px!important;
    background: var(--mention-color)!important; 
}

.separator-2zcjq8 {
    width: auto!important;
}

.clickable-2ap7je .header-2o-2hj:hover, .selected-WP3kCM .header-2o-2hj {
    background-color: #0a0a0a!important;
}

.uploadModal-2ifh8j .inner-3nWsbo {
    border-color: var(--primary-color)!important;
}

.lookInverted-2D7oAl.colorBrand-3pXr91 {
    background-color: var(--primary-color)!important;
    color: whitesmoke!important;
}

.markup-2BOw-j code.inline {
    padding: 0em!important;
    background-color: #0a0a0a!important;
}

.container-3baos1 {
    margin-bottom: 0px!important;
}

.wrapper-1BJsBx.selected-bZ3Lue .childWrapper-anI2G9, .wrapper-1BJsBx .childWrapper-anI2G9 {
    background-color: var(--channels-color)!important;
    color: var(--primary-color)!important;
}

.selected-aXhQR6 .layout-2DM8Md {
    transition: text ease-in 0.1s;
    border-radius: 0px;
    background: var(--mention-color)!important;
    color: white;
}

.metadata-3WGS0M {
    color: #cbcbcb!important;
}

.modeConnected-2IEL4z .name-3_Dsmg, .modeConnected-2IEL4z:hover .name-3_Dsmg, .modeSelected-1zApJ_ .name-3_Dsmg {
    color: white;
}

.circleIconButton-jET_ig {
    color: #a0db15!important;
    background: #0a0a0a!important;
}

.layout-2DM8Md {
    transition: all ease-in 0.1s;
}

.theme-dark .placeholderWrapper-3FaLtZ {
    background: var(--mention-color)!important;
}

.mention {
    background: var(--chat-color)!important;
    color: var(--link-color)!important;
    text-shadow: 0 0 5px #a0db15!important;
    border-radius: 2px;
}

.lookFilled-1Gx00P.colorBrand-3pXr91 {
    background-color: #75a00d!important;
}

.name-3YKhmS, .tierTooltipTitle-1EIbL_ {
    color: whitesmoke!important;
}

.lookFilled-1Gx00P.colorGreen-29iAKY {
    background-color: var(--channels-text-selected)!important;
}

.children-19S4PO:after {
    display: none!important;
}

.markup-2BOw-j a {
    color: var(--link-color)!important;
    text-shadow: 0 0 5px var(--link-color)!important;
}

.membersGroup-v9BXpm {
    height: 45px!important;
}

.anchor-3Z-8Bb {
    color: #a0db15;
}

.cancelButton-3hVEV6, .downloadButton-23tKQp {
    color: #a0db15!important;
}

.expandedFolderBackground-2sPsd- {
    background-color: var(--dropdown-color);
}

.edited-DL9ECl {
    margin-left: 0.2px;
    margin-top: 0.03em;
}

.mediaBarGrabber-1FqnbN, .mediaBarProgress-1xaPtl, .mediaBarProgress-1xaPtl:after, .mediaBarProgress-1xaPtl:before {
    background-color: var(--link-color)!important;
}

.emptyResultsWrap-3Kv0LQ {
    color: #0a0a0a!important;
}

.theme-dark .messagesPopout-24nkyi,
.theme-dark .jumpButton-3DTcS_,
.theme-dark .messageGroupWrapper-o-Zw7G:hover .actionButtons-1sUUug {
    background-color: #0a0a0a!important;
    box-shadow: none;
}

.theme-dark .option-1l2vXE {
    background-color: #111;
}

.theme-dark .consent-1AQ-th, .theme-light .consent-1AQ-th {
    background-color: var(--link-color);
}

.blockquoteDivider-2hH8H6 {
    background-color: var(--link-color);
}

.base-PmTxvP {
    font-size: 10px!important;
}

.numberBadge-2s8kKX.base-PmTxvP.da-numberBadge {
    background-color: var(--link-color)!important;
    width: 20px;
}

.lowerBadge-29hYVK.da-lowerBadge {
    transform: translate(1px, 0px)!important;
}

/* LiveIcon. */

.live-2o_S8y {
    background-color: var(--primary-color)!important;
}

/* Chat(Input)box. */

.inner-zqa7da:before {
    content:'';
    position:absolute;
    width: 99.76%;
    height:2px;
    background:linear-gradient(to right,#37b1da 0,#c948cd 50%,#cce335 100%);
    top:1.8px;
    left:1px;
}

.button-2vd_v_,
.button-3AYNKb {
    padding: 4px!important;
    margin: 10px;
}
/*Update stuff*/

.form-2fGMdU:before{
    display:none;
}

  /* Discord Message box */
:root {
    --color-brand-lighter: #a2e427;
}
.input-cIJ7To,
.scrollableContainer-2NUZem {
    background-color: #141414;
    transition: background-color 0.2s ease, border-color 0.2s ease;
    border: 1px solid transparent;
    outline: none;
}
.input-cIJ7To:hover,
.scrollableContainer-2NUZem:hover {
    border-color: #96c83c!important;;
    background-color: #181818!important;;
      box-shadow: 0px 0px 3px 1px #96c83c;
}
.input-cIJ7To:focus-within,
.scrollableContainer-2NUZem:focus-within {
    background-color: #1f1f1f!important;;
    border-color: var(--color-brand-lighter)!important;
}
.scrollableContainer-2NUZem {
    border: 1px solid transparent;
    border-radius: 5px;
}
/*Change selected channel side color*/
.containerDefault--pIXnN.selected-3LIHYU {
    border-left: 1px solid #9fca2b;
    box-shadow: 0px 0px 3px 1px #96c83c!important;
}
/* Pings */
.numberBadge-2s8kKX {
  animation: animatedPing 1.3s infinite ease-in-out;
}
@keyframes animatedPing {
  0% {
    transform: rotate(-12deg);
  }
  50% {
    transform: rotate(12deg) scale(1.2);
  }
  100% {
    transform: rotate(-10deg);
  }
}
/* Hover Channels animated */
.mainContent-u_9PKf:hover {
  animation: UserModalButtons 0.5s normal ease;}
.mainContent-u_9PKf .noWrap-3jynv6 {width: 100px;opacity: 1;}
.mainContent-u_9PKf {transition: 0.2s;}
.mainContent-u_9PKf:hover {transition: 0.2;}
@keyframes UserModalButtons {
  0% {
    transform: translateY(0px);
  }
  45% {
    transform: translateY(-5px);
  }
  90% {
    transform: translateY(0px);
  }
}



#app-mount .privateChannels-1nO12o .searchBar-6Kv8R2 {
  position: absolute;
  bottom: 20px;
  right: 5px;
  height: 40px;
  width: 42px;
  border: none;
  border-radius: 40px;
  background: linear-gradient(to bottom right, var(--main-color, #323232), var(--hover-color, #323232));
  box-shadow: 2px 10px 10px var(--shadow, rgba(75, 75, 75, 0.399)) !important;
  overflow: hidden;
  cursor: pointer;
  transition: all .4s ease-in-out;
  pointer-events: all;
  padding: 0;
}

#app-mount .privateChannels-1nO12o .searchBar-6Kv8R2 .searchBarComponent-32dTOx {
  background-color: transparent !important;
}
/** 
* @name gamesense theme 
* @version 1.2 
* @description Fixed gamesense theme 
* @author Xyhlo#9766 
* @socials This is my instagram be nice and leave a like or a comment: maxyiiiss
*/
@import url('https://fonts.googleapis.com/css?family=Raleway');
@import url(https://codedotspectra.github.io/themes/mini-themes/settingsIcons.css);
:root{
     --title-gradient:linear-gradient(to right,#37b1da ,#c948cd ,#cce335, #37b1da);
     --primary-color:#75a00d;
     --background-secondary: #0a0a0a;
    --background-primary: #070707;
     --outline-color:#0a0a0a;
     --outline-lightcolor:#303030;
     --app-color:#0b0b0b;
     --channels-color:#111;
     --channeltextarea-background: #000;
     --channels-darker:#0c0c0c;
     --channels-selected:#191919;
     --channels-text-selected:#9fca2b;
     --chat-color:#0b0b0b;
     --mention-color:#1f1f1f;
     --scrollbar-bg:#202020;
     --scrollbar-thumb:#414141;
     --text-input:#191919;
     --dropdown-color:#232323;
     --link-color:#96c83c;
     --channel-radius:5px;
     --text-color:#cbcbcb;
     --text-darker:#b0b0b0;
     --font:'Verdana',Helvetica,Arial,sans-serif;
     --important-notification-l:#f84747;
     --important-notification:#d12020;
     
}
.search-1FM8Qc:not(.open-3y3yI_) .searchBar-zdmu7v {
     width: 27px;
     transition: 0.25s;
     background-color: transparent;
}
.search-1FM8Qc:not(.open-3y3yI_):hover .searchBar-zdmu7v {
     width: 240px;
     background-color: var(--background-tertiary);
}
.search-1FM8Qc:not(.open-3y3yI_) .iconContainer-1RqWJj {
     transform: scale(1.3);
     transition: 0.25s;
}
.search-1FM8Qc:not(.open-3y3yI_):hover .iconContainer-1RqWJj {
     transform: scale(1);
}
.icon-18rqoe {
     color: var(--text-normal)
}
.scrollableContainer-2NUZem {
     padding-right: 11px ;
}
.typeWindows-2-g3UY{
     animation: rgbTop 3s infinite linear;
    
}
@keyframes rgbTop {
     0% {
         background-position: 1920px;
         
    }
     100% {
         background-position: 0px;
         
    }
    
}
.scrollableContainer-2NUZem::-webkit-scrollbar {
     display: none;
    
}
.avatarHintInner-2HUAWj {
     font-size: 8px !important;
    
}

/* Change ping badge color */
.numberBadge-37OJ3S {
    background-color: #6e9601 !important
}

/*Remove Stage Discovery Tab*/
#private-channels [href=\"/discovery\"] {
    display: none
}

/*Remove Library Tab*/
#private-channels [href=\"/library\"] {
    display: none
}

/*Remove Nitro Tab*/
#private-channels [href=\"/store\"] {
    display: none
}

/*Unread channels rainbow wave*/
.wrapper-NhbLHG.modeUnread-3Cxepe .name-28HaxV {
     background-image: linear-gradient(to left,rgb(51, 255, 0), rgb(255, 230, 0), red, rgb(234, 0, 255), rgb(0, 140, 255), rgb(51, 255, 0));
     animation: gradient-border 3s linear infinite;
     background-size: 400% 100%;
     color: transparent !important;
     -webkit-background-clip: text;
     position: relative;
     z-index: 1;
    
}
@keyframes gradient-border {
     0%, 200% {
         background-position: 0 0;
         
    }
     99.999999999999999% {
         background-position: 130% 0;
         
    }
    
}
 .expandedFolderBackground-1cujaW,.expandedFolderIconWrapper-Huv7r{
    /*couleur fichier ouvert*/
     background-color:#0a0a0a!important;
    
}
.members-3WRCEx, .members-3WRCEx > .content-2a4AW9 {
     background: #0a0a0a !important;
    
}
#app-mount .wrapper-1Rf91z {
     background-color: #0a0a0a !important;
    
}

/*Change selected channel side color*/
.containerDefault-YUSmu3.selected-2TbFuo {
     border-left: 6px solid #9fca2b;
    
}
#app-mount .container-2nx-BQ, #app-mount .bd-switch-body {
     width: 20px;
     height: 20px;
     background: transparent !important;
     
}
 #app-mount .container-2nx-BQ .slider-32CRPX, #app-mount .bd-switch-body .bd-switch-slider {
     left: -6px !important;
     
}
 #app-mount .container-2nx-BQ .slider-32CRPX > rect, #app-mount .bd-switch-body .bd-switch-slider rect {
     height: 20px !important;
     width: 20px !important;
     x: 4px !important;
     y: 0px !important;
     rx: 5;
     fill: var(--background-tertiary);
     
}
.wrapper-1_HaEi::before {
    /*Guild wrapper background*/
     content: '';
     position: absolute;
     top: 0;
     left: 0;
     bottom: 0;
     right: 0;
     background: #0a0a0a;
     background-size: cover;
    
}
.tree-3agP2X, .scroller-3X7KbA,.wrapper-1_HaEi {
    /*Guild subcontainer*/
     background: transparent;
    
}

/*connections look cooler*/
.connectedAccount-2Jb-Z0:active{
     border-width: 1.2px 1.2px 1.2px 1.2px;
     transform: translateY(1px);
     transition: 0.1s;
    
}
.connectedAccount-2Jb-Z0{
     border: solid #151b27;
     border-width: 1.2px 1.2px 3px 1.2px;
     border-radius: 4px;
     transition: 0.1s;
    
}
.scrollableContainer-2NUZem {
     border: 1px solid #9fca2b;
     
}
 svg.homeIcon-FuNwkv{
     color:transparent;
    
}

/* Custom home icon */
#app-mount .listItemWrapper-KhRmzM .childWrapper-1j_1ub {
     background: url('https://i.ytimg.com/vi/meqVOjIO45A/maxresdefault.jpg') center/cover no-repeat;
    
}
.homeIcon-FuNwkv {
     display: none;
    
}
*{
     font-size: 15px!important;
     font-family:var(--font)!important;
}
strong{
     font-weight:normal;
}
a{
     color:var(--link-color);
}
body{
     font-family:var(--font)!important;
     background-color:var(--app-color) ;
}
input,textarea{
     font-family:var(--font)!important;
}
.wrapper-1Rf91z{
    background-color:#191919;
    
}
.appMount-2yBXZl{
     left:6px;
     top:6px;
     height:calc(100vh - 12px);
     width:calc(100vw - 12px);
     box-shadow:0 0 0 1px #3c3c3c,0 0 0 4px #282828,0 0 0 5px #3c3c3c,0 0 0 6px #0a0a0a;
     background-color:var(--channels-color);
}
.typeWindows-2-g3UY{
     height:25px;
     background:var(--primary-color);
     margin-top:-0.5px!important;
     margin-left:1px;
     margin-right:1px;
     background:var(--title-gradient);
     box-shadow:inset 0 -23px 0 0 var(--app-color),inset 0 -24px 0 0 rgba(0,0,0,0.5);
     opacity:1.0;
     z-index:50;
     border-bottom:1px solid var(--outline-lightcolor)
}
*/
.typeWindows-2-g3UY:hover{
    \theight:20px;
    \ttransition: all .6s;
    \topacity: 1;
    
}
*/
.winButton-iRh8-Z{
     top:2px!important
}
.wordmark-2u86JB{
     opacity:1.0;
     font-family:'Raleway';
}
.wordmark-2u86JB::before{
     content:'game';
     font-size:14px;
     z-index:1000;
     position:fixed;
     display:inline-block;
     color:var(--text-color);
     height:auto;
     top:12px;
     left:12px;
     background-color:transparent;
}
.mention-1f5kbO {
     background-color: var(--primary-color)!important;
    
}
.wordmark-2u86JB::after{
     content:'sense';
     font-size:14px;
     z-index:1000;
     position:fixed;
     display:inline-block;
     color:var(--primary-color);
     height:auto;
     top:12px;
     left:52px;
     background-color:transparent;
}
.winButtonClose-3Q8ZH5{
     height:33px;
    
}
.winButtonClose-3Q8ZH5:hover{
     background-color: transparent;
    
}
.winButtonMinMax-3RsPUg{
    height:33px;
    
}
.winButtonMinMax-3RsPUg:hover{
     background-color: transparent;
    
}
.wordmark-2u86JB svg{
     display:none
}
.theme-dark .guildsWrapper{
     background:var(--channels-darker);
     box-shadow:inset -1px 0 0 0 #303030,inset -2px 0 0 0 #000
}
.guildsWrapper .guildsAdd-21_Id{
     border-radius:0;
     background:var(--chat-color);
     border:1px dashed var(--outline-lightcolor);
     color:var(--outline-lightcolor)
}
.guildsWrapper-1Rf91z .guildsAdd-21_Id:hover{
     color:var(--text-color);
     border-color:var(--text-color)
}
.guildsWrapper-1Rf91z .guildsAdd-21_Id-inner{
     top:-2px
}
.guildsWrapper-1Rf91z .guilds-1q_RqH .guilds-1q_RqH+.guilds-1q_RqH{
     margin-bottom:25px;
     margin-top:25px
}
.guildInner-3DSoA4{
     border-radius:0!important
}
.guildsWrapper-1Rf91z .guilds-1q_RqH .guild-1EfMGQ+.guild-1EfMGQ{
     margin-top:25px
}
.guildsWrapper-1Rf91z .guilds-1q_RqH .friendsOnline-_wi_fM{
     padding-bottom:10px;
     font-size:9px
}
.guildsWrapper-1Rf91z .guilds-1q_RqH .guild-1EfMGQ.selected-ML3OIq:before{
     box-shadow:0 1px 0 0 #303030,-1px 2px 0 0 #000,0 -1px 0 0 #303030,-1px -2px 0 0 #000;
     background:var(--channels-color);
     border-radius:0;
     height:70px;
     margin-top:-35px;
     width:75px;
     -webkit-transition:none;
     transition:none
}
.guildsWrapper-1Rf91z .guilds-1q_RqH .guild-1EfMGQ .guildInner-3DSoA4{
     background:var(--chat-color)!important
}
.guildsWrapper-1Rf91z .guilds-1q_RqH .guild-1EfMGQ.selected-ML3OIq .guildInner-3DSoA4 a{
     background-color:var(--primary-color)!important;
     transition:all .3s ease
}
.guildsWrapper-1Rf91z .guilds-1q_RqH .guild-1EfMGQ.selected-ML3OIq .guildInner-3DSoA4{
     background-color:var(--primary-color)!important;
     transition:all .3s ease
}
.guildInner-3DSoA4{
     background-color:var(--primary-color);
     border-radius:var(--channel-radius)!important;
     transition:all .3s ease
}
.guildInner-3DSoA4:hover{
     background-color:var(--primary-color)!important;
     transition:all .3s ease
}
.guild-1EfMGQ.active .guildInner-3DSoA4{
     background:var(--primary-color)!important
}
.guildsWrapper-1Rf91z .guildseparator-1X4GQ1{
     display:none
}
.guildsAdd-21_IdK {
    \tborder-radius: 10%;
    
}
.avatar-large,.avatar-profile,.avatar-small,.avatar-xlarge,.avatar-xsmall,.avatar-xxlarge{
     border-radius:var(--channel-radius)!important
}
.avatarHint-1qgaV3{
    \tborder-radius:var(--channel-radius)!important
}
.container-PNkimc{
     background:none!important
}
.base-2jDfDU{
     border-radius:0!important
}
.header-2o-2hj{
     background:var(--channels-darker);
     box-shadow:none!important;
     border-bottom:1px solid var(--outline-lightcolor)
}
.header-2o-2hj:hover{
     background:var(--channels-selected)
}
.container-1UB9sr{
     border-top:1px solid var(--outline-lightcolor);
     border-bottom:0;
     background:var(--chat-color);
     font-size:11px;
     padding:5px 10px 5px 10px
}
.channels-Ie2l6A.vertical-V37hAW.flex-3BkGQD.directionColumn-3pi1nm {
     background:var(--channels-color);
     border-right:1px solid var(--outline-lightcolor)
}
.name-3M0b8v{
     font-size:13px;
     font-weight:700
}
.contentSelectedText-3wUhMi{
     background:var(--channels-selected)
}
.nameSelectedText-sp_EUw,.nameSelectedVoice-1qSph5,svg.colorSelectedText-1y4Wvs.icon-sxakjD,svg.colorSelectedVoice-Xcb_9R.icon-sxakjD{
     color:var(--channels-text-selected)!important;
     opacity:1
}
.theme-dark .member-3W1lQa:hover .content-OzHfo4, .theme-dark .member-3W1lQa.popout-open .content-OzHfo4, .theme-dark .member-3W1lQa.popout-open:hover .content-OzHfo4 {
    \tbackground:var(--channels-selected)
}
.contentHoveredText-2D9B-x,.contentHoveredVoice-3p_NEO,.contentHoveredVoice-3p_NEO:active,.contentSelectedVoice-1WDIBM:active{
     background:none!important
}
.container-2Thooq{
     background:var(--channels-darker);
     border-top:1px solid var(--outline-lightcolor)
}
.popout{
     background:var(--dropdown-color)!important;
     border:solid 1px var(--outline-color)!important;
     border-radius:1px
}
.small-popout-box{
     background:var(--dropdown-color)!important;
     border:solid 1px var(--outline-color)!important;
     border-radius:1px
}
.theme-dark .messagesPopoutWrap-1MQ1bW .footer-1kmXd4 {
     background: var(--channels-darker)!important;
    
}
.theme-dark .messagesPopoutWrap-1MQ1bW {
     border-radius: 1px;
     background: var(--channels-color)!important;
     box-shadow: 0 0 0 1px #323232,0 0 0 2px #0a0a0a!important;
    
}
.theme-dark .messagesPopoutWrap-1MQ1bW .header-ykumBX {
     -webkit-box-shadow: 0 2px 3px 0 rgba(0,0,0,20%);
     background-color: #35393e;
     box-shadow: 0 2px 3px 0 rgba(0,0,0,.2);
     background: var(--channels-darker)!important;
    
}
.option-popout .btn-item,.option-popout .btn-item:hover{
     color:var(--text-color)
}
.contextMenu-HLZMGh{
     background:var(--dropdown-color)!important;
     border:solid 1px var(--outline-color)!important;
     border-radius:1px;
     box-shadow:none!important;
}
.item-1Yvehc{
     font-size:11px!important
}
.item-1Yvehc:hover{
     background:var(--outline-lightcolor)!important;
     border-radius:0
}
.itemSubMenu-1vN_Yn{
     background-color:var(--dropdown-color)!important
}
.menu-Sp6bN1{
     border-radius:1px;
    \tbackground:var(--chat-color)!important;
    \tbox-shadow:0 0 0 1px #323232,0 0 0 2px #0a0a0a!important;
    
}
.item-1GzJrl{
     color:var(--text-color);
     font-size:11px!important
}
.item-1GzJrl:hover{
     border-radius:0!important;
     color:var(--text-color);
     background:var(--outline-lightcolor)!important
}
.separator-2zcjq8{
     border-color:var(--outline-lightcolor)!important;
     width:100%
}
.title-3qD0b-,.titleCall-_b9o8P{
     background:var(--channels-darker)!important;
     box-shadow:inset 0 -1px 0 var(--outline-lightcolor)!important
}
.channelName-3stJzi{
     font-size:13px;
     color:var(--text-color)!important
}
.channelName-3stJzi svg{
     width:14px;
     color:var(--text-color)
}
.channelIcon-MsmKOO{
     top:4px
}
.topic-2QX7LI{
     font-size:11px
}
.messagesWrapper-3lZDfY {
     background:none!important
}
.chat-3bRxxu>.content-yTz4x3{
     background:var(--chat-color)!important
}
.embedPill-1Zntps{
     background:var(--primary-color)!important
}
.embedInner-1-fpTo{
     background:var(--channels-darker)!important;
     border-radius:1px!important;
     border-color:var(--outline-lightcolor)!important
}
.message-group{
     padding:15px 0
}
.message-group h2 strong{
     font-size:13px
}
.timestampCozy-2hLAPV{
     font-size:9px
}
.markup-eYLPri{
     font-size:11px;
     line-height:1.4em
}
.markup-eYLPri pre{
     border-radius:1px!important;
     border:none!important;
     box-shadow:0 0 0 1px #323232,0 0 0 2px #101010!important
}
.markup-eYLPri pre code{
     font-size:13px;
     background:var(--dropdown-color)!important
}
.hljs-section{
     color:var(--primary-color)!important
}
.theme-dark .divider-3gKybi.dividerRed-MKoLlr .dividerContent-2L12VI>span {
     background:#113!important
}
.theme-dark .divider-3gKybi.dividerRed-MKoLlr .dividerContent-2L12VI:after, .theme-dark .divider-3gKybi.dividerRed-MKoLlr .dividerContent-2L12VI:before {
    background:var(--important-notification)!important;
    border-color: transparent !important;
    
}
.theme-dark .divider-3gKybi span {
    \tbackground:0b0b0b!important
}
.imageWrapper-oMkQl4{
     border-radius:3px
}
.chat-3bRxxu form{
     background:none!important;
     box-shadow:none!important
}
.inner-zqa7da{
     border-radius:0!important;
     background:var(--text-input)!important;
     box-shadow:inset 0 0 0 1px #323232,inset 0 0 0 2px #101010
}
.channelTextArea-rNsIhG .inner-zqa7da .textArea-2Spzkt{
     font-size:11px;
     line-height: 1.6rem;
    
}
.theme-dark .channelTextArea-rNsIhG {
    \tborder-top:none;
    
}
.innerEnabled-3g80kR .textArea-2Spzkt{
     font-size:11px;
     line-height:.80rem;
     margin:12px 2px 2px 0;
     padding:5px 38px 8px 10px
}
.textAreaEnabled-3vQ5WZ{
     padding:5px 38px 8px 0
}
.typing-2GQL18{
     background:none!important;
     font-size:8px!important;
     padding-left:1px
}
.typing-2GQL18 .ellipsis-1e7x0D{
     display:none
}
.scroller-2FKFPG.members-3WRCEx{
     background:var(--channels-darker)!important;
     border-left:solid 1px var(--outline-lightcolor);
     color:red
}
.image-33JSyf{
    \tborder-radius:var(--channel-radius)!important
}
.mask-3OgeRz{
    \t-webkit-mask: none;
    
}
::-webkit-scrollbar-thumb{
     border:none!important;
     border-radius:0!important;
     background:#414141!important
}
::-webkit-scrollbar{
     width:6px!important
}
::-webkit-scrollbar-track-piece{
     border:none!important;
     border-radius:0!important;
     background:#2d2d2d!important
}
.scroller-kQBbkU::-webkit-scrollbar{
     border:none!important;
     border-radius:0!important;
     background:#414141!important;
     height:100px!important;
}
.scroller-wrap .scroller::-webkit-scrollbar{
     width:6px!important
}
.scrollerWrap-2lJEkd .scroller::-webkit-scrollbar-track-piece{
     border:none!important;
     border-radius:0!important;
     background:#2d2d2d!important
}
.scrollerWrap-2lJEkd.scroller::-webkit-scrollbar-thumb{
     border:none!important;
     border-radius:0!important;
     background:#414141!important
}
.scrollerWrap-2lJEkd .scroller::-webkit-scrollbar{
     width:6px!important
}
.scrollerWrap-2lJEkd .scroller::-webkit-scrollbar-track-piece{
     border:none!important;
     border-radius:0!important;
     background:#2d2d2d!important
}
.tooltip,.tooltip.tooltip-black,.tipsy-inner{
     border-radius:1px!important
}
.bd-blue .tooltip-red,.tooltip.tooltip-red{
     background-color:var(--important-notification)
}
.bd-blue .tooltip-red.tooltip-top:after{
     border-top-color:var(--important-notification)
}
.bd-blue .tooltip-red.tooltip-left:after{
     border-left-color:var(--important-notification)
}
.bd-blue .tooltip-red.tooltip-bottom:after{
     border-bottom-color:var(--important-notification)
}
.bd-blue .tooltip-red.tooltip-right:after,.tooltip.tooltip-red.tooltip-right:after{
     border-right-color:var(--important-notification)
}
.tooltip.tooltip-right:after,.tooltip.tooltip-left:after{
     margin-top:-8px
}
.tooltip.tooltip-brand,.tooltip.tooltip-black,.tipsy-inner{
     background:var(--channels-darker)!important;
     border:solid 1px var(--outline-lightcolor)!important;
     border-radius:1px;
     padding:5px 10px;
     font-size:11px;
     font-weight:400;
     line-height:14px;
     text-align:center
}
.tooltip.tooltip-brand.tooltip-right:after,.tooltip.tooltip-black.tooltip-right:after{
     border-radius:0;
     border-right:8px solid var(--outline-lightcolor)!important;
     border-top:8px solid transparent!important;
     border-bottom:8px solid transparent!important
}
.tooltip.tooltip-brand.tooltip-top:after,.tooltip.tooltip-black.tooltip-top:after,.tipsy-se .tipsy-inner:after{
     border-radius:0;
     border-right:8px solid transparent!important;
     border-top:8px solid var(--outline-lightcolor)!important;
     border-left:8px solid transparent!important
}
.tooltip.tooltip-brand.tooltip-left:after,.tooltip.tooltip-black.tooltip-left:after{
     border-radius:0;
     border-left:8px solid var(--outline-lightcolor)!important;
     border-top:8px solid transparent!important;
     border-bottom:8px solid transparent!important
}
.tooltip.tooltip-brand.tooltip-bottom:after,.tooltip.tooltip-black.tooltip-bottom:after{
     border-radius:0;
     border-right:8px solid transparent!important;
     border-bottom:8px solid var(--outline-lightcolor)!important;
     border-left:8px solid transparent!important
}
.checkbox{
     width:8px;
     height:8px;
     background:#4c4c4c;
     background:linear-gradient(to bottom,#4c4c4c 0,#333 100%);
     border-radius:0!important;
     border:1px solid var(--outline-color)
}
.checkbox .checkbox-inner{
     height:8px;
     width:8px;
     border:0
}
.checkbox .checkbox-inner span{
     border:0;
     border-radius:0;
     background:linear-gradient(to bottom,#4c4c4c 0,#333 100%)
}
.checkbox .checkbox-inner input[type=checkbox]:checked+span{
     background:linear-gradient(to bottom,#9cc728 0,#7aa506 100%);
     transition:5.0
}
.checkbox .checkbox-inner input[type=checkbox]:checked+span:after{
     content:none
}
.checkbox .checkbox-inner+span{
     white-space:nowrap;
     color:var(--text-color);
     font-size:11px
}
.grabber-2GQyvM{
     border-radius:5px!important;
     margin-left:-6px!important
}
.bar-1Bhnl9{
     background:linear-gradient(to bottom,#343434 0,#444 100%)!important;
     border-radius:0!important;
     border:1px solid var(--outline-color)
}
.barFill-2Bh7CX{
     background:linear-gradient(to bottom,#99c427 0,#699404 100%)!important
}
.bubble-3we2di{
     background:var(--channels-darker)!important;
     border:solid 1px var(--outline-lightcolor)!important;
     border-radius:1px;
     font-size:10px;
     color:var(--text-color)
}
.bubble-3we2di:before{
     border-top-color:var(--outline-lightcolor)
}
#friends{
     background:var(--channels-darker)!important
}
.friends-table{
     background:var(--chat-color)!important;
     border-top:1px solid var(--outline-lightcolor)
}
.tab-bar-item.tab-bar-item-primary{
     background:linear-gradient(to bottom,#232323 0,#191919 100%)!important;
     border-radius:0!important;
     box-shadow:inset 0 0 0 1px #0a0a0a,inset 0 0 0 2px #323232;
     font-size:11px;
     padding:5px 15px 5px 15px!important;
     color:var(--text-color)!important
}
.tab-bar-item.tab-bar-item-primary:hover{
     background:linear-gradient(to bottom,#282828 0,#1e1e1e 100%)!important
}
.tab-bar-item.tab-bar-item-primary.selected{
     background:linear-gradient(to bottom,#1e1e1e 0,#0f0f0f 100%)!important;
     color:var(--primary-color)!important
}
.tab-bar-item{
     color:var(--text-color)!important
}
.tab-bar-item.selected{
     border-radius:0!important;
     background:var(--outline-lightcolor)!important;
     color:var(--primary-color)!important
}
.tab-bar-item:hover{
     border-radius:0!important;
     background:var(--outline-lightcolor)!important
}
.friends-table .friends-row:hover{
     border-radius:0!important;
     background:var(--outline-lightcolor)!important
}
.friends-table .friends-row .friends-column-actions .friends-action:hover{
     background-color:var(--outline-color)!important
}
.private-channels .channel.selected a,.private-channels .channel a:hover{
     background:var(--outline-lightcolor);
     color:var(--text-color)!important;
     margin-right:10px!important
}
.friend-table-add-wrapper .friend-table-add-header{
     background:var(--channels-darker)!important;
     border-bottom:1px solid var(--outline-lightcolor)!important;
     box-shadow:none!important;
     padding-top:10px
}
.friend-table-add-wrapper h2{
     font-size:12px!important
}
.friend-table-add-wrapper h3{
     font-size:11px!important
}
.friend-table-add-wrapper .friend-table-add-description{
     font-size:11px!important
}
.wrapper-1xW8FI{
     padding-right:5px
}
.inner-1lPVFp{
     border-radius:1px;
     border-color:var(--outline-lightcolor);
     background-color:var(--chat-color)
}
.wrapper-1cBijl{
     border-radius:0!important;
     background:var(--text-input)!important;
     box-shadow:inset 0 0 0 1px #323232,inset 0 0 0 2px #101010
}
.friend-table-suggestions-header{
     padding:20px 30px 16px!important
}
.btn{
     background:var(--primary-color)!important
}
.modal-3HD5ck{
     border-radius:0;
     background:var(--channels-darker)!important;
     box-shadow:inset 0 0 0 1px #0a0a0a,inset 0 0 0 2px #323232!important
}
.h4-AQvcAz{
     font-size:13px;
     color:var(--text-color)!important
}
.primary-jw0I4K{
     font-size:12px!important;
     color:var(--text-color)!important
}
.message-group-blocked{
     border-radius:0!important;
     background:var(--dropdown-color)!important
}
.message-group-blocked .message-group-blocked-btn{
     background:var(--channels-color)!important;
     font-size:11px
}
.mention{
     color:var(--primary-color)!important;
     background:var(--mention-color)!important
}
.popout{
     box-shadow:none!important;
     border:var(--outline-lightcolor)!important
}
.userPopout-3XzG_A{
     border-radius:1px;
     box-shadow:0 0 0 1px #323232,0 0 0 2px #0a0a0a!important
}
.headerPlaying-j0WQBV,.headerNormal-T_seeN{
     background:var(--channels-darker)!important
}
.activity-11LB_k{
     background:var(--primary-color)
}
.body-3iLsc4,.footer-1fjuF6{
     background:var(--channels-color)!important
}
.textRow-1sENuL{
     font-size:13px
}
.quickMessage-2XpSaN{
     border-radius:0!important;
     background:var(--text-input)!important;
     border:0;
     box-shadow:inset 0 0 0 1px #323232,inset 0 0 0 2px #101010;
     font-size:11px
}
.role-2irmRk{
     font-size:10px
}
.note-3kmerW textarea{
     border-radius:0!important;
     background:var(--text-input)!important;
     border:0;
     box-shadow:inset 0 0 0 1px #323232,inset 0 0 0 2px #101010;
     font-size:11px
}
.search-results-wrap{
     background:var(--channels-color)!important;
     border-left:1px solid var(--outline-lightcolor)
}
.search-header{
     box-shadow:none!important;
     background:var(--channels-darker)!important;
     border-bottom:1px solid var(--outline-lightcolor)
}
.search-header .tab.selected{
     color:var(--primary-color)!important;
     border-color:var(--primary-color)!important
}
.search-results-wrap .channel-separator .channel-name{
     background:none!important;
     font-size:13px
}
.search-results-wrap .search-result:before,.search-results-wrap .search-result:after{
     background:none!important
}
.search-results-wrap .search-result .hit{
     background:var(--outline-lightcolor)!important;
     border-radius:1px;
     border:1px solid var(--outline-color)!important;
     box-shadow:none!important
}
.search-popout{
     box-shadow:none!important;
     background:var(--channels-color);
     box-shadow:0 0 0 1px #323232,0 0 0 2px #0a0a0a!important;
     border-radius:0
}
.search-popout .option{
     font-size:13px;
     height:24px;
}
.search-popout .option.selected:before{
     height:24px;
}
.search-popout .option.selected{
     background:var(--outline-lightcolor);
}
.search-popout .search-option .filter,.option.history .answer{
     color:var(--text-darker);
}
.search-popout .option:after,.search-popout .option.selected:after{
     background:0;
}
.search-popout .search-query{
     border-bottom:0;
}
.system-message{
     font-size:13px;
}
.topSectionNormal-2-vo2m{
     background:var(--channels-darker)!important;
}
.body-3ND3kc{
     background:var(--channels-color)!important;
}
.tabBar-2MuP6- .tab-bar-item.selected{
     border-color:var(--primary-color)!important;
     background:none!important;
}
.tabBar-2MuP6- .tab-bar-item:hover{
     background:none!important;
}
.topSectionPlaying-1J5E4n{
     background:var(--channels-darker);
}
.autocomplete-3NRXG8{
     background:var(--channels-darker)!important;
     border:1px solid var(--outline-lightcolor);
}
.selectorSelected-1_M1WV{
     border-radius:1px;
     background:var(--channels-color)!important;
}
.buttonBrandInvertedDefault-uUmgsD{
     background:var(--primary-color)!important;
     color:#fff
}
.chat-3bRxxu .newMessagesBar-mujexs{
     background:var(--primary-color)!important
}
.unreadBar-elBRZx{
     background:var(--primary-color)!important
}
.emojiPicker-3m1S-j{
     background:none!important
}
.emojiPicker-3m1S-j .header-1nkwgG .search-bar{
     background:none!important
}
.emojiPicker-3m1S-j .stickyHeader-1SS0JU{
     background:0
}
.emojiPicker-3m1S-j .category-2U57w6{
     color:var(--primary-color)
}
.search-bar.search-bar-light .search-bar-inner{
     border-radius:0!important;
     background:var(--text-input)!important;
     box-shadow:inset 0 0 0 1px #323232,inset 0 0 0 2px #101010
}
.emojiPicker-3m1S-j .categories-1feg4n .item-16cXuq.selected-39BZ4S{
     border-bottom-color:var(--primary-color)
}
.emojiPicker-3m1S-j .scroller-3vODG7 .emojiItem-109bjA.selected-39BZ4S{
     background-color:var(--dropdown-color)
}
.search-bar input{
     font-size:12px!important
}
.form header{
     color:var(--primary-color)!important
}
.form-deprecated,.form.deprecated{
     background:var(--channels-darker)!important;
     box-shadow:inset 0 0 0 1px var(--outline-lightcolor)
}
.form-deprecated .form-inner,.form.deprecated .form-inner{
     background:none!important
}
.form-deprecated .form-actions,.form.deprecated .form-actions{
     background:none!important;
     border-color:var(--outline-lightcolor)
}
.create-guild-container.deprecated .action{
     background:var(--channels-color);
     border:1px solid var(--outline-lightcolor)
}
.create-guild-container.deprecated .action.join:hover .btn{
     background-color:var(--primary-color)!important
}
.form-deprecated .btn-default,.form.deprecated .btn-default,.form-deprecated .btn-default:hover,.form.deprecated .btn-default:hover{
     background:none!important;
     border-bottom:0;
     color:var(--text-color)!important
}
.create-guild-container.deprecated .join-server h5{
     font-size:14px;
     color:var(--primary-color)
}
.create-guild-container.deprecated p{
     font-size:12px
}
.bd-blue .create-guild-container .join-server .sample-link{
     font-size:13px
}
.guild-form li .control-group input[type=text]{
     padding-left:10px
}
.form.deprecated .control-group input[type=text]{
     border-radius:0!important;
     background:var(--text-input)!important;
     border:0;
     box-shadow:inset 0 0 0 1px #323232,inset 0 0 0 2px #101010;
     color:var(--text-color);
     font-size:12px
}
.form.deprecated .control-group input[type=text]:focus{
     border:0
}
.bd-blue .avatar-uploader-inner{
     background:var(--primary-color)!important
}
.regionSelect-3lf4eE .regionSelectInner-24f4Ce,.regionSelect-3lf4eE:hover .regionSelectInner-24f4Ce,.regionSelect-3lf4eE:hover button{
     border-radius:1px;
     border-color:var(--outline-lightcolor)
}
.regionSelect-3lf4eE button,.regionSelect-3lf4eE:hover button{
     border-radius:1px;
     border-color:var(--outline-lightcolor);
     color:var(--text-color);
     background:var(--channels-color)
}
.regionSelectModal-12e-57{
     background:var(--channels-darker)
}
.regionSelectModal-12e-57 .regionSelectModalOption-2DSIZ3{
     background:var(--channels-color);
     border:1px solid var(--outline-lightcolor)
}
.regionSelectModal-12e-57 .regionSelectModalOption-2DSIZ3:hover{
     border-color:var(--primary-color)
}
.message-group a{
     color:var(--link-color)!important
}
.wrapper-2NJDcI{
     background:#232529
}
.themed-popout{
     background:var(--channels-color)!important;
     border-radius:1px!important;
     border:1px solid var(--outline-lightcolor)!important
}
.themed-popout .header{
     background:var(--channels-darker)!important;
     box-shadow:none!important;
     border-bottom:1px solid var(--outline-lightcolor)
}
.themed-popout .footer{
     background:none!important;
     border-top:1px solid var(--outline-lightcolor)
}
.private-channel-recipients-invite .friend{
     background:var(--channels-color)!important
}
.search-bar .search-bar-inner{
     border-radius:0!important;
     background:var(--text-input)!important;
     box-shadow:inset 0 0 0 1px #323232,inset 0 0 0 2px #101010;
}
.private-channel-recipients-invite .footer button{
     background:var(--primary-color)!important;
}
.video-eAcneW{
     background:var(--channels-color);
     border-bottom:1px solid var(--outline-lightcolor)
}
.footer-2yfCgX{
     background:none!important
}
.tiles-2aXG_k{
     background:var(--channels-color)!important
}
.selectorButtonSelected-1j4DmC,.buttonBrandFilled-3Mv0Ra,.buttonBrandFilled-3Mv0Ra:hover,.buttonBrandFilled-3Mv0Ra:active{
     background:var(--primary-color)
}
.imageSelected-4Kl81J{
     border-color:var(--primary-color)
}
.quickswitcher-pKcM9U{
     background:var(--channels-darker)!important;
     border-radius:1px;
     border:1px solid var(--outline-lightcolor);
     box-shadow:none
}
.input-3r5zZY{
     border-radius:0!important;
     background:var(--text-input)!important;
     box-shadow:inset 0 0 0 1px #323232,inset 0 0 0 2px #101010!important;
     color:var(--text-color)!important
}
.note-3HfJZ5{
     margin-left:0
}
.note-3kmerW textarea{
     padding-top:6px;
     padding-left:10px
}
.form-deprecated .form-header,.form.deprecated .form-header{
     background:0
}
.wrapper-O5i5-0 .instantInviteModal-3vhcvC .form-header header{
     color:var(--primary-color);
     font-size:14px
}
.wrapper-O5i5-0 .instantInviteModal-3vhcvC .blurb-zsamaY{
     color:var(--text-color);
     font-size:11px
}
.wrapper-O5i5-0 .instantInviteModal-3vhcvC .checkbox .checkbox-inner span{
     border:0
}
.wrapper-O5i5-0 .instantInviteModal-3vhcvC .expireText-34b09Y{
     color:var(--text-color)
}
.cclipboardInputInner-1EXMA3{
     border-radius:0!important;
     background:var(--text-input)!important;
     box-shadow:inset 0 0 0 1px #323232,inset 0 0 0 2px #101010;
     border:none!important
}
.wrapper-O5i5-0 .instantInviteModal-3vhcvC .clipboardInputInner-RLx2hK input{
     background:0;
     font-size:16px;
     color:var(--primary-color)
}
.wrapper-O5i5-0 .instantInviteModal-3vhcvC .copy-3nFbq8{
     background:var(--primary-color);
     border:0;
     font-size:11px
}
.cclipboardInputInner-1EXMA3 button:first-of-type:before{
     background:none!important
}
.wrapper-O5i5-0{
     background:0
}
.Select-control,.Select-control:hover,.Select-control:active{
     border-radius:0!important;
     background:var(--text-input)!important;
     box-shadow:inset 0 0 0 1px #323232,inset 0 0 0 2px #101010;
     border:none!important
}
.has-value.Select--single>.Select-control .Select-value .Select-value-label,.has-value.is-pseudo-focused.Select--single>.Select-control .Select-value .Select-value-label,.has-value.Select--single>.Select-control .Select-value .Select-value-label{
     color:var(--text-color)
}
.wrapper-O5i5-0 .instantInviteModalAdvanced-3qJETM .checkbox .checkbox-inner span{
     border:0
}
.Select-option,.Select-option.is-focused{
     background:none!important;
     color:var(--text-color)!important
}
.Select-menu-outer{
     background:var(--channels-color);
     border:1px solid var(--outline-lightcolor)
}
.titleWrapper-1l0xT9 {
    \tbackground:var(--channels-darker);
    
}
.theme-dark .members-3WRCEx {
    \tbackground:var(--channels-darker);
    
}
.theme-dark .messageGroupWrapper-o-Zw7G {
    tbackground-color: var(--chat-color);
    tborder-color: var(--outline-lightcolor);
    tborder-radius: 0px;
    border-width: 1px;
    
}
.theme-dark .divider-3gKybi.dividerRed-MKoLlr .dividerContent-2L12VI {
    color: var(--important-notification);
    
}
.theme-dark .divider-3gKybi.dividerRed-MKoLlr .dividerContent-2L12VI:after, .theme-dark .divider-3gKybi.dividerRed-MKoLlr .dividerContent-2L12VI:before {
    border-color: var(--important-notification-l);
    
}

/* fixed bg */
.messages-3amgkR,.searchBar-3TnChZ,.scroller-1JbKM,.activityPanel-9icbyU,.container-YkUktl,.scroller-2TZvBN,.scroller-WSmht3,.scroller-2wx7Hm,.bodyInner-245q0L,.contentRegionScroller-2_GT_N,.sidebarRegionScroller-FXiQOh,.container-ZMc96U.themed-Hp1KC_,.friendsTable-133bsv,.friendsTable-133bsv .friendsTableBody-1ZhKif,.scroller-29cQFV,.emptyStateLarge-1nQX5A,.theme-dark .layout-1cQCv2,#bd-pub-button,.customScroller-m1-jZn,.scroller-305q3I,.header-2w6VV8,.inner-ZyuQk0,.theme-dark .footer-1Ip3Sd,.container-1zzFcN,.platform-win .scroller-2TZvBN,.scroller-2qwVWY,.footer-C9oLp9,.noResults-1ceiMB, .scroller-1Kbkqa,.theme-dark .messagesPopout-24nkyi.markup-eYLPri code.inline,.barButtonBase-3UKlW2,.uploadModal-2ifh8j,.uploadModal-2ifh8j .footer-3mqk7D,.emojiPicker-3m1S-j,.listeningAlong-6YvYsc,.bda-dark .emojiPicker-3m1S-j .category-2U57w6,.emptyResultsWrap-3Kv0LQ,.searchHeader-1l-wpR,.measurement-36xDqs,.panel-2ZFCRb,.modalBody-LuOFny,.perksModalContentWrapper-2HU6uL,.scroller-5bBood {
     background: #0a0a0a!important;
    
}
.markup-eYLPri pre code {
     box-shadow: 0 0 0 1px #3c3c3c,0 0 0 2px #282828,0 0 0 3px #3c3c3c,0 0 0 4px #0a0a0a;
     border-radius: 0px!important;
     transition: all ease-in 0.1s;
     background: var(--mention-color)!important;
    
}
.contextMenu-HLZMGh {
     box-shadow: 0 0 0 1px #3c3c3c,0 0 0 4px #282828,0 0 0 5px #3c3c3c,0 0 0 6px #0a0a0a!important;
     border-top: solid 2px var(--channels-text-selected)!important;
     border-radius: 0px!important;
     background: var(--mention-color)!important;
     
}

/* bda-emojipicker */
.bda-dark .emojiPicker-3m1S-j {
     box-shadow: 0 0 0 1px #3c3c3c,0 0 0 4px #282828,0 0 0 5px #3c3c3c,0 0 0 6px #0a0a0a!important;
     border-radius: 0px!important;
     background: var(--mention-color)!important;
     
}
.bda-dark .emojiPicker-3m1S-j:before {
     content:'';
     position:absolute;
     width:100%;
     height:2px;
     background:linear-gradient(to right,#37b1da 0,#c948cd 50%,#cce335 100%);
     top:0px;
     left:-1px;
    
}
.bda-dark .emojiPicker-3m1S-j .category-2U57w6 {
     background-color: var(--mention-color)!important;
    
}

/* blocked */
.wrapper-2SplAX {
     box-shadow: 0 0 0 1px #3c3c3c,0 0 0 4px #282828,0 0 0 5px #3c3c3c,0 0 0 6px #0a0a0a!important;
     border-radius: 0px!important;
     background: var(--mention-color)!important;
     
}
.wrapper-2SplAX:before {
     content:'';
     position:absolute;
     width:100%;
     height:2px;
     background:linear-gradient(to right,#37b1da 0,#c948cd 50%,#cce335 100%);
     top:10px;
     left:-1px;
     
}

/* bottag */
.botTagRegular-2HEhHi {
     background-color: var(--primary-color);
    
}
.botTag-7aX5WZ {
     font-size: 12px!important;
    
}

/* add role gui */
.container-1S70rv {
     box-shadow: 0 0 0 1px #3c3c3c,0 0 0 4px #282828,0 0 0 5px #3c3c3c,0 0 0 6px #0a0a0a!important;
     border-radius: 0px!important;
     background: var(--mention-color)!important;
     
}
.container-1S70rv .headerText-27z-EV {
     font-size: 10px!important;
    
}
.theme-dark .row-1Ib2uD {
     background-color: var(--mention-color);
    
}
.container-1S70rv:before {
     content:'';
     position:absolute;
     width:100%;
     height:2px;
     background:linear-gradient(to right,#37b1da 0,#c948cd 50%,#cce335 100%);
     top:1px;
     left:-1px;
    
}

/* view profile text */
.avatarHintInner-Dco91E {
     font-size: 12px!important;
     font-weight: normal!important;
     text-transform: none!important;
    
}

/* gif selector */
.autocomplete-3NRXG8 {
     box-shadow: 0 0 0 1px #3c3c3c,0 0 0 4px #282828,0 0 0 5px #3c3c3c,0 0 0 6px #0a0a0a!important;
     border-radius: 0px!important;
     background: var(--mention-color)!important;
     
}
.autocomplete-3NRXG8:before {
     content:'';
     position:absolute;
     width:100%;
     height:2px;
     background:linear-gradient(to right,#37b1da 0,#c948cd 50%,#cce335 100%);
     top:0px;
     left:-1px;
     
}

/* messages popout */
 .theme-dark .messagesPopoutWrap-1MQ1bW {
     box-shadow: 0 0 0 1px #3c3c3c,0 0 0 4px #282828,0 0 0 5px #3c3c3c,0 0 0 6px #0a0a0a!important;
     border-radius: 0px!important;
     background: var(--mention-color)!important;
     
}
.theme-dark .messagesPopoutWrap-1MQ1bW:before {
     content:'';
     position:absolute;
     width:100%;
     height:2px;
     background:linear-gradient(to right,#37b1da 0,#c948cd 50%,#cce335 100%);
     top:0px;
     left:-1px;
     
}
.themedPopout-1TrfdI .header-2Kf7Yu{
     z-index: 0!important;
    
}

/* connection status */
.container-1ILvLB {
     box-shadow: 0 0 0 1px #3c3c3c,0 0 0 4px #282828,0 0 0 5px #3c3c3c,0 0 0 6px #0a0a0a!important;
     border-radius: 0px!important;
     background: var(--mention-color)!important;
     
}
.theme-dark .container-1ILvLB .header-2C89wJ,.theme-dark .container-1ILvLB section {
     background: var(--mention-color)!important;
    
}
.theme-dark .container-1ILvLB .header-2C89wJ:before {
     content:'';
     position:absolute;
     width:100%;
     height:2px;
     background:linear-gradient(to right,#37b1da 0,#c948cd 50%,#cce335 100%);
     top:0px;
     left:-1px;
     
}

/* ----------- */
.contextMenu-HLZMGh:before {
     content:'';
     position:absolute;
     width:101%;
     height:2px;
     background:linear-gradient(to right,#37b1da 0,#c948cd 50%,#cce335 100%);
     top:-2px;
     left:-1px;
    
}

/* random button */
.selectorButtonSelected-336oUc {
     background-color: var(--primary-color)!important;
    
}
.container-3cGP6G {
     box-shadow: 0 0 0 1px #3c3c3c,0 0 0 4px #282828,0 0 0 5px #3c3c3c,0 0 0 6px #0a0a0a!important;
     border-radius: 0px!important;
     background: var(--mention-color)!important;
    
}
.container-3cGP6G:before {
     content:'';
     position:absolute;
     width:101%;
     height:2px;
     background:linear-gradient(to right,#37b1da 0,#c948cd 50%,#cce335 100%);
     top:-2px;
     left:-1px;
     
}
.barButtonBase-3UKlW2 {
     background-color: var(--mention-color)!important;
     box-shadow: 0 0 0 1px #3c3c3c,0 0 0 4px #282828,0 0 0 5px #3c3c3c,0 0 0 6px #0a0a0a!important;
     border-radius: 0px!important;
     opacity: 1!important;
     color: whitesmoke!important;
    
}
.container-36u7Lw {
     font-size: 12px!important;
    
}
.role-2irmRk {
     border-radius: 0px!important;
    
}
.roleName-2ZJJYR {
     font-size: 12px!important;
    
}
.userSettingsAccount-2eMFVR div:nth-child(2)>div:nth-child(2)>.viewBody-2Qz-jg:hover {
    \tfilter: blur(0)
}
.userSettingsAccount-2eMFVR div:nth-child(2)>div:nth-child(2)>.viewBody-2Qz-jg {
    \tfilter: blur(5px);
    \ttransition: 250ms filter ease-in-out
}
.content-3at_AU {
     margin: 1px;
    
}
.modeSelected-1zApJ_ .content-3at_AU, .modeSelected-1zApJ_:hover .content-3at_AU {
     border-radius: 0px!important;
     background: var(--mention-color)!important;
     
}
.theme-dark .attachment-33OFj0 {
     box-shadow: 0 0 0 1px #3c3c3c,0 0 0 2px #282828,0 0 0 3px #3c3c3c,0 0 0 4px #0a0a0a;
     border-radius: 0px!important;
     background: var(--mention-color)!important;
    
}
.weightSemiBold-1WYsXZ {
     font-weight: 400!important;
     font-size: 14px!important;
    
}
.userPopout-3XzG_A.da-userPopout {
     box-shadow: 0 0 0 1px #3c3c3c,0 0 0 4px #282828,0 0 0 5px #3c3c3c,0 0 0 6px #0a0a0a!important;
     border-radius: 0px!important;
     background: var(--mention-color)!important;
     
}
.userPopout-3XzG_A.da-userPopout:before {
     content:'';
     position:absolute;
     width:100%;
     height:2px;
     background:linear-gradient(to right,#37b1da 0,#c948cd 50%,#cce335 100%);
     top:0px;
     left:0px;
    
}
.activity-11LB_k {
     background-color: var(--channels-selected)!important;
    
}
.menu-Sp6bN1 {
     box-shadow: 0 0 0 1px #3c3c3c,0 0 0 4px #282828,0 0 0 5px #3c3c3c,0 0 0 6px #0a0a0a!important;
     border-radius: 0px!important;
     background: var(--mention-color)!important;
     
}
.separator-2zcjq8 {
     width: auto!important;
    
}
.clickable-2ap7je .header-2o-2hj:hover, .selected-WP3kCM .header-2o-2hj {
     background-color: #0a0a0a!important;
    
}
.uploadModal-2ifh8j .inner-3nWsbo {
     border-color: var(--primary-color)!important;
    
}
.lookInverted-2D7oAl.colorBrand-3pXr91 {
     background-color: var(--primary-color)!important;
     color: whitesmoke!important;
    
}
.markup-eYLPri code.inline {
     padding: 0em!important;
     background-color: #0a0a0a!important;
    
}
.container-YkUktl {
     margin-bottom: 0px!important;
    
}
.wrapper-3kah-n.selected-1Drb7Z .childWrapper-1j_1ub, .wrapper-3kah-n .childWrapper-1j_1ub {
     background-color: var(--channels-color)!important;
     color: var(--primary-color)!important;
    
}
.selected-1-Z6gm .layout-1qmrhw {
     transition: text ease-in 0.1s;
     border-radius: 0px;
     background: var(--mention-color)!important;
     color: white;
    
}
.metadata-3WGS0M {
     color: #cbcbcb!important;
    
}
.modeConnected-2IEL4z .name-3_Dsmg, .modeConnected-2IEL4z:hover .name-3_Dsmg, .modeSelected-1zApJ_ .name-3_Dsmg {
     color: white;
    
}
.circleIconButton-jET_ig {
     color: #a0db15!important;
     background: #0a0a0a!important;
    
}
.layout-1qmrhw {
     transition: all ease-in 0.1s;
    
}
.theme-dark .placeholderWrapper-3FaLtZ {
     background: var(--mention-color)!important;
    
}
.mention {
     background: var(--chat-color)!important;
     color: var(--link-color)!important;
     text-shadow: 0 0 5px #a0db15!important;
     border-radius: 2px;
    
}
.lookFilled-1Gx00P.colorBrand-3pXr91 {
     background-color: #75a00d!important;
    
}
.name-3YKhmS, .tierTooltipTitle-1EIbL_ {
     color: whitesmoke!important;
    
}
.lookFilled-1Gx00P.colorGreen-29iAKY {
     background-color: var(--channels-text-selected)!important;
    
}
.children-3xh0VB:after {
     display: none!important;
    
}
.markup-eYLPri a {
     color: var(--link-color)!important;
     text-shadow: 0 0 5px var(--link-color)!important;
    
}
.membersGroup-2eiWxl {
     height: 45px!important;
    
}
.anchor-1MIwyf {
     color: #a0db15;
    
}
.cancelButton-oOSTov, .downloadButton-2HLFWN {
     color: #a0db15!important;
    
}
.expandedFolderBackground-2sPsd- {
     background-color: var(--dropdown-color);
    
}
.edited-DL9ECl {
     margin-left: 0.2px;
     margin-top: 0.03em;
    
}
.mediaBarGrabber-FvJKJg, .mediaBarProgress-1xaPtl, .mediaBarProgress-1xaPtl:after, .mediaBarProgress-1xaPtl:before {
     background-color: var(--link-color)!important;
    
}
.emptyResultsWrap-3Kv0LQ {
     color: #0a0a0a!important;
    
}
.theme-dark .messagesPopout-24nkyi,.theme-dark .jumpButton-3DTcS_,.theme-dark .messageGroupWrapper-o-Zw7G:hover .actionButtons-1sUUug {
     background-color: #0a0a0a!important;
     box-shadow: none;
    
}
.theme-dark .option-1l2vXE {
     background-color: #111;
    
}
.theme-dark .consent-1AQ-th, .theme-light .consent-1AQ-th {
     background-color: var(--link-color);
    
}
.blockquoteDivider-363utW {
     background-color: var(--link-color);
    
}
.base-3IDx3L {
     font-size: 10px!important;
    
}
.numberBadge-37OJ3S.base-3IDx3L.da-numberBadge {
     background-color: var(--link-color)!important;
     width: 20px;
    
}
.lowerBadge-3WTshO.da-lowerBadge {
     transform: translate(1px, 0px)!important;
    
}

/* LiveIcon. */
.live-2o_S8y {
     background-color: var(--primary-color)!important;
    
}

/* Chat(Input)box. */
.inner-zqa7da:before {
     content:'';
     position:absolute;
     width: 99.76%;
     height:2px;
     background:linear-gradient(to right,#37b1da 0,#c948cd 50%,#cce335 100%);
     top:1.8px;
     left:1px;
    
}
.button-2vd_v_,.button-2fCJ0o {
     padding: 4px!important;
     margin: 10px;
    
}

/*Update stuff*/
.form-2fGMdU:before{
     display:none;
    
}
 
/* Discord Message box */
:root {
     --color-brand-lighter: #a2e427;
    
}
.input-2z42oC,.scrollableContainer-15eg7h {
     background-color: #141414;
     transition: background-color 0.2s ease, border-color 0.2s ease;
     border: 1px solid transparent;
     outline: none;
    
}
.input-2z42oC:hover,.scrollableContainer-15eg7h:hover {
     border-color: #96c83c!important;
    ;
     background-color: #181818!important;
    ;
     box-shadow: 0px 0px 3px 1px #96c83c;
    
}
.input-2z42oC:focus-within,.scrollableContainer-15eg7h:focus-within {
     background-color: #1f1f1f!important;
    ;
     border-color: var(--color-brand-lighter)!important;
    
}
.scrollableContainer-15eg7h {
     border: 1px solid transparent;
     border-radius: 5px;
    
}

/*Change selected channel side color*/
.containerDefault-YUSmu3.selected-2TbFuo {
     border-left: 1px solid #9fca2b;
     box-shadow: 0px 0px 3px 1px #96c83c!important;
    
}

/* Pings */
.numberBadge-37OJ3S {
     animation: animatedPing 1.3s infinite ease-in-out;
    
}
@keyframes animatedPing {
     0% {
         transform: rotate(-12deg);
         
    }
     50% {
         transform: rotate(12deg) scale(1.2);
         
    }
     100% {
         transform: rotate(-10deg);
         
    }
    
}

/* Hover Channels animated */
.mainContent-20q_Hp:hover {
     animation: UserModalButtons 0.5s normal ease;
}
.mainContent-20q_Hp .noWrap-hBpHBz {
    width: 100px;
    opacity: 1;
}
.mainContent-20q_Hp {
    transition: 0.2s;
}
.mainContent-20q_Hp:hover {
    transition: 0.2;
}
@keyframes UserModalButtons {
     0% {
         transform: translateY(0px);
         
    }
     45% {
         transform: translateY(-5px);
         
    }
     90% {
         transform: translateY(0px);
         
    }
    
}
#app-mount .privateChannels-oVe7HL .searchBar-3TnChZ {
     position: absolute;
     bottom: 20px;
     right: 5px;
     height: 40px;
     width: 42px;
     border: none;
     border-radius: 40px;
     background: linear-gradient(to bottom right, var(--main-color, #323232), var(--hover-color, #323232));
     box-shadow: 2px 10px 10px var(--shadow, rgba(75, 75, 75, 0.399)) !important;
     overflow: hidden;
     cursor: pointer;
     transition: all .4s ease-in-out;
     pointer-events: all;
     padding: 0;
    
}
#app-mount .privateChannels-oVe7HL .searchBar-3TnChZ .searchBarComponent-3N7dCG {
     background-color: transparent !important;
    
}
.privateChannels-oVe7HL .searchBar-3TnChZ .inner-1NoIT5 {
     height: 100%;
     width: 100%;
    
}
#app-mount .privateChannels-oVe7HL .searchBar-3TnChZ .searchBarComponent-3N7dCG::after {
     content: '';
     position: absolute;
     height: 100%;
     width: 30px;
     bottom: 1px;
     right: 5px;
     background-color: #9fca2b!important;
     -webkit-mask: url('data:image/svg+xml,%3Csvg xmlns=\"http://www.w3.org/2000/svg\" height=\"24px\" viewBox=\"0 0 24 24\" width=\"24px\" fill=\"%23000000\"%3E%3Cpath d=\"M0 0h24v24H0z\" fill=\"none\"/%3E%3Cpath d=\"M15.5 14h-.79l-.28-.27C15.41 12.59 16 11.11 16 9.5 16 5.91 13.09 3 9.5 3S3 5.91 3 9.5 5.91 16 9.5 16c1.61 0 3.09-.59 4.23-1.57l.27.28v.79l5 4.99L20.49 19l-4.99-5zm-6 0C7.01 14 5 11.99 5 9.5S7.01 5 9.5 5 14 7.01 14 9.5 11.99 14 9.5 14z\"/%3E%3C/svg%3E') center/cover no-repeat;
    
}
#app-mount .privateChannels-oVe7HL .searchBar-3TnChZ .searchBarComponent-3N7dCG::before {
     content: 'Search Direct Messages';
     position: absolute;
     top: 50%;
     transform: translateY(-25%);
     width: 180px;
     bottom: 0;
     right: 0.3vw;
     color: #9fca2b;
     opacity: .5;
     font-size: 12px;
     line-height: 100%;
     transition: all 1s ease-in-out;
     pointer-events: none;
    
}
#app-mount .privateChannels-oVe7HL .searchBar-3TnChZ .searchBarComponent-3N7dCG {
     color: transparent;
    
}
#app-mount .privateChannels-oVe7HL .searchBar-3TnChZ:hover {
     width: 200px;
    
}
.circleIconButton-1VxDrg{
     background-color: rgba(29, 29, 29, 0.5);
    
}
.peopleList-3c4jOR,.scroller-hE2gWq{
    background-color: #0a0a0a!important;
}
.searchOption-351dTI{
    background-color:#0a0a0a;
}
#app-mount .searchOption-351dTI:hover{
    background-color:#74a00d33;
}
.container-2McqkF{
    background-color:#0a0a0a!important;
}
#app-mount .option-2KkUJO::after{
    background:#0a0a0a;
}
.unreadMentionsBar-ZXXoOHgo{
    background-color: green!important;
}
.theme-dark .root-g14mjS{
    background-color: black;
}
.theme-dark .footer-31IekZ{
    background-color: black;
}
.container-YkUktl{
    margin-right:5px;
    outline:solid 5px rgb(70, 70, 70)!important;
}
.activityPanel-9icbyU{
    margin-right:5px;
    margin-bottom: 5px;
    outline:solid 5px rgb(70, 70, 70)!important;
}
.peopleList-2VBrVI{
    background-color: #0a0a0a!important;
    margin-top: -1px;
}
.scroller-3j5xK2{
    background-color: #0a0a0a!important;
    margin-top: -1px;
}




/*Quarel snips*/
#app-mount .chatContent-3KubbW .form-3gdLxP{background:var(--bar-background-primary);padding:21px 16px 0;margin-bottom:0;bottom:-3px;margin:0;margin-top:-3px}
#app-mount .chatContent-3KubbW .form-3gdLxP .channelTextArea-1FufC0{margin-top:0;margin-bottom:24px}
#app-mount .chatContent-3KubbW .form-3gdLxP::before{content:none}
#app-mount .chatContent-3KubbW .form-3gdLxP .content-2M_BlY,#app-mount .chatContent-3KubbW .form-3gdLxP .buttonContainer-KMz3Ex{margin-bottom:8px}

#app-mount .autocomplete-3NRXG8{bottom:calc(100% + 29px)}
#app-mount .positionLayer-1cndvf.layer-2aCOJ3{bottom:calc(var(--bar-height) + 8px)!important}
#app-mount .wrapper-2SplAX{margin-bottom:16px}
#app-mount .unreadMentionsIndicatorBottom-3RJMnQ{bottom:var(--bar-height)}
#app-mount #status-picker{margin-bottom:20px}
#app-mount .typing-2GQL18{bottom:0}
.attachButtonPlus-3IYelE{fill:#fff;d:path("M7 12.001C7 10.8964 6.10457 10.001 5 10.001C3.89543 10.001 3 10.8964 3 12.001C3 13.1055 3.89543 14.001 5 14.001C6.10457 14.001 7 13.1055 7 12.001ZM14 12.001C14 10.8964 13.1046 10.001 12 10.001C10.8954 10.001 10 10.8964 10 12.001C10 13.1055 10.8954 14.001 12 14.001C13.1046 14.001 14 13.1055 14 12.001ZM19 10.001C20.1046 10.001 21 10.8964 21 12.001C21 13.1055 20.1046 14.001 19 14.001C17.8954 14.001 17 13.1055 17 12.001C17 10.8964 17.8954 10.001 19 10.001Z")}
.modeSelected-3DmyhH .content-1gYQeQ,.modeSelected-3DmyhH:hover .content-1gYQeQ{background-color:var(--background-modifier-selected);width:250px;height:35px;margin-left:-1px;margin-right:-10px}
.content-1gYQeQ{width:250px;height:35px;margin-left:-1px;margin-right:-10px}
.icon-3zI3d2,.mainContent-uDGa6R{margin-left:5px;font-size:15px}
.name-3BUDLf{margin-left:5px;font-size:15px;margin-left:10px}
.icon-3zI3d2{height:25px;width:25px;margin-top:-6px;margin-left:2px}

#app-mount .wrapper-1VLyxH svg:not(:root){overflow:visible}
#app-mount .wrapper-1VLyxH foreignObject{-webkit-mask:none;mask:none}
#app-mount .wrapper-1VLyxH .dots-1BwzZQ circle:nth-child(1){cy:-8!important;cx:-8.5!important}
#app-mount .wrapper-1VLyxH .dots-1BwzZQ circle:nth-child(2){cy:-8!important;cx:-2.25!important}
#app-mount .wrapper-1VLyxH .dots-1BwzZQ circle:nth-child(3){cy:-8!important;cx:4!important}
#app-mount .wrapper-1VLyxH .mask-1FEkla > rect[x="22"]{x:-10;y:5;width:.5px;height:21px;position:fixed}
#app-mount .wrapper-1VLyxH .cursorDefault--wfhy5 rect{x:-49;y:-53}
#app-mount .wrapper-1VLyxH .pointerEvents-9SZWKj[x="14.5"]{fill:rgba(0,0,0,0.5)!important;width:30px;height:30px;x:1;y:1}
#app-mount .wrapper-1VLyxH > svg > foreignObject img{border-radius:var(--rs-avatar-shape)}
#app-mount .wrapper-1VLyxH svg[width="25"][height="15"] > rect{rx:calc(var(--rs-avatar-shape) * 2)!important;ry:calc(var(--rs-avatar-shape) * 2)!important}
#app-mount .wrapper-1VLyxH rect{x:0;y:0;width:100%;height:100%;-webkit-mask:none;mask:none;display:block!important;rx:var(--rs-avatar-shape)!important;ry:var(--rs-avatar-shape)!important;fill:transparent!important;stroke-width:var(--rs-width)}
#app-mount .wrapper-1VLyxH rect[fill="#43b581"],#app-mount .wrapper-1VLyxH rect[fill="rgba(67, 181, 129, 1)"],#app-mount .wrapper-1VLyxH rect[mask*=online]{stroke:var(--rs-online-color)}
#app-mount .wrapper-1VLyxH rect[fill="#faa61a"],#app-mount .wrapper-1VLyxH rect[fill="rgba(250, 166, 26, 1)"],#app-mount .wrapper-1VLyxH rect[mask*=idle]{stroke:var(--rs-idle-color)!important}
#app-mount .wrapper-1VLyxH rect[fill="#f04747"],#app-mount .wrapper-1VLyxH rect[fill="rgba(240, 71, 71, 1)"],#app-mount .wrapper-1VLyxH rect[mask*=dnd]{stroke:var(--rs-dnd-color)!important}
#app-mount .wrapper-1VLyxH rect[fill="#593695"],#app-mount .wrapper-1VLyxH rect[mask*=streaming]{stroke:var(--rs-streaming-color)!important}
#app-mount .wrapper-1VLyxH rect[fill="#747f8d"],#app-mount .wrapper-1VLyxH rect[mask*=offline],#app-mount .wrapper-1VLyxH rect[fill=NaN]{stroke:var(--rs-offline-color)}
#app-mount .wrapper-1VLyxH rect[fill="#747f8d"],#app-mount .wrapper-1VLyxH rect[mask*=invisible],#app-mount .wrapper-1VLyxH rect[fill="rgba(116, 127, 141, 1)"]{stroke:var(--rs-invisible-color)}
#app-mount .wrapper-1VLyxH[style*="width: 80px;"] rect{width:80px;height:80px;pointer-events:none}
#app-mount .wrapper-1VLyxH[style*="width: 80px;"] img{-webkit-clip-path:inset(calc(var(--rs-large-spacing) + 1px) calc(var(--rs-large-spacing) + 1px) round var(--rs-avatar-shape));clip-path:inset(calc(var(--rs-large-spacing) + 1px) calc(var(--rs-large-spacing) + 1px) round var(--rs-avatar-shape))}
#app-mount .wrapper-1VLyxH[style*="width: 32px;"] rect{width:32px;height:32px;x:-14.5;y:-17;position:relative;z-index:0}
#app-mount .wrapper-1VLyxH rect{x:0;y:0;width:80%;height:100%;-webkit-mask:none;mask:none;display:block!important;rx:var(--rs-avatar-shape)!important;ry:var(--rs-avatar-shape)!important;fill:transparent!important;stroke-width:var(--rs-width)}
:root{--rs-small-spacing:0;--rs-large-spacing:0;--rs-width:2px;--rs-avatar-shape:50%;--rs-online-color:#1df594;--rs-idle-color:#faa61a;--rs-dnd-color:#f04747;--rs-offline-color:#636b75;--rs-streaming-color:#643da7;--rs-invisible-color:#747f8d;--rs-phone-visible:block;--rs-phone-color:var(--rs-online-color)}
#app-mount .wrapper-1VLyxH[style*="width: 80px;"]:after{left:unset;right:-2px;top:unset;bottom:-2px;transform:none}
#app-mount .avatarHint-1qgaV3 foreignObject{-webkit-mask:none;mask:none;border-radius:VAR(--rs-avatar-shape)}
.scrollableContainer-15eg7h{background-color:var(--bar-background-primary)}
#app-mount{--bar-height:86px}
#app-mount .container-YkUktl{position:absolute;background-color:var(--bar-background-primary);bottom:16px;max-width:223px}
#app-mount .sidebar-1tnWFu{padding-bottom:var(--bar-height)}
#app-mount .sidebar-1tnWFu::before{content:"";position:absolute;background-color:var(--bar-background-primary);width:100%;height:var(--bar-height);bottom:0;box-shadow:120px 80px 40px 20px rgba(4,252,252,0.808)}
#app-mount .chatContent-3KubbW .form-3gdLxP{background:var(--bar-background-primary);padding:21px 16px 0;margin-bottom:0;bottom:-3px;margin:0;margin-top:-3px}
#app-mount .chatContent-3KubbW .form-3gdLxP .channelTextArea-1FufC0{margin-top:0;margin-bottom:24px}
#app-mount .chatContent-3KubbW .form-3gdLxP::before{content:none}
#app-mount .chatContent-3KubbW .form-3gdLxP .content-2M_BlY,#app-mount .chatContent-3KubbW .form-3gdLxP .buttonContainer-KMz3Ex{margin-bottom:8px}

#app-mount .applicationStore-2nk7Lo::before:hover{content:"";position:absolute;background-color:var(--bar-background-primary);width:100%;height:var(--bar-height);bottom:0}
#app-mount .autocomplete-3NRXG8{bottom:calc(100% + 29px)}
#app-mount .positionLayer-1cndvf.layer-2aCOJ3{bottom:calc(var(--bar-height) + 8px)!important}
#app-mount .wrapper-2SplAX{margin-bottom:16px}
#app-mount .unreadMentionsIndicatorBottom-3RJMnQ{bottom:var(--bar-height)}
#app-mount #status-picker{margin-bottom:20px}
#app-mount .typing-2GQL18{bottom:0}
.attachButtonPlus-3IYelE{fill:#fff;d:path("M7 12.001C7 10.8964 6.10457 10.001 5 10.001C3.89543 10.001 3 10.8964 3 12.001C3 13.1055 3.89543 14.001 5 14.001C6.10457 14.001 7 13.1055 7 12.001ZM14 12.001C14 10.8964 13.1046 10.001 12 10.001C10.8954 10.001 10 10.8964 10 12.001C10 13.1055 10.8954 14.001 12 14.001C13.1046 14.001 14 13.1055 14 12.001ZM19 10.001C20.1046 10.001 21 10.8964 21 12.001C21 13.1055 20.1046 14.001 19 14.001C17.8954 14.001 17 13.1055 17 12.001C17 10.8964 17.8954 10.001 19 10.001Z")}
.modeSelected-3DmyhH .content-1gYQeQ,.modeSelected-3DmyhH:hover .content-1gYQeQ{background-color:var(--background-modifier-selected);width:250px;height:35px;margin-left:-1px;margin-right:-10px}
.content-1gYQeQ{width:250px;height:35px;margin-left:-1px;margin-right:-10px}
.children-1MGS9G{margin-right:15px}
.unread-36eUEm{width:1.25px;height:20px;border-radius:0;margin-left:3px;margin-top:-9px}
.item-2LIpTv{width:1.75px;height:30px;border-radius:0;margin-left:3px;margin-top:-0}
.expandedFolderBackground-1cujaW{background-color:var(--background-tertiary)}
.listItem-GuPuDH:hover{background-color:#292D30}
.button-3bklZh [aria-label="Reply"]{display:none}
::-webkit-scrollbar{display:var(--scrollbars)}
[class="button-3bklZh"][aria-label="Edit"]{display:none}
.isHeader-2bbX-L{transition:.5s;border-color:rgba(0,0,0,0);background-color:rgba(0,0,0,0)}
.layers-OrUESM>.layer-86YKbF:first-child{transform:scale(1)!important;opacity:1!important}
.layers-OrUESM>.layer-86YKbF:nth-child(2),.perksModal-fSYqOq{background-color:rgba(22,22,22,0.842)!important;backdrop-filter:blur(8px)}
.contentRegionScroller-2_GT_N,.contentRegion-3HkfJJ,.standardSidebarView-E9Pc3j,.sidebarRegionScroller-FXiQOh{background:transparent}

.homeIcon-FuNwkv path{display:none}
.homeIcon-FuNwkv,.theme-light .wrapper-3kah-n.selected-1Drb7Z .homeIcon-FuNwkv,.theme-light .wrapper-3kah-n:hover .homeIcon-FuNwkv,.guilds-2JjMmN.theme-dark .homeIcon-FuNwkv{background-image:var(--home-icon);background-position:50%;background-repeat:no-repeat;background-size:28px 28px;margin:0;height:100%;width:100%}
.theme-light .homeIcon-FuNwkv{background-image:var(--home-icon)}
.voiceUser-3nRK-K>.content-1Tgc42>.icons-2mwuFp svg>path:last-child{fill:var(--background-accent)}
:root{--popup-color:var(--background-accent)}
.tooltipPrimary-3qLMbS{background:var(--popup-color)!important}
.tooltipPointer-3L49xb{border-top-color:var(--popup-color)!important}
.headerSpotify-zpWxgT,.topSectionSpotify-1lI0-P{background:var(--spotify-color)}
.attachButtonPlay-1ATmb5{color:var(--spotify-color)}
.headerStreaming-2FjmG,.topSectionStreaming-1Tpf5X{background:var(--streaming-color)}
.streamerModeEnabledBtn-2nlJTD{background-color:var(--streaming-color)}
.headerPlaying-j0WQBV,.topSectionPlaying-1J5E4n{background:var(--playing-color)}
.theme-dark .headerNormal-T_seeN{background:var(--modal-normal-primary-color)}
.theme-dark .body-3iLsc4,.theme-dark .footer-1fjuF6{background-color:var(--modal-normal-secondary-color)}
.scroller-3X7KbA{background-color:var(--serverlist-background)}
.members-3WRCEx,.members-3WRCEx>div{background-color:var(--memberlist-background)}
.mentioned-Tre-dv:before{background-color:var(--mentioned-line)}
.theme-dark .tooltipPrimary-3qLMbS,.theme-light .tooltipPrimary-3qLMbS{background-color:var(--background-accent)}
.header-2BwW8b{border-radius:0 0 12px 12px}
.isUnread-3Lojb-,.unreadPill-3nEWYM{border-color:var(--background-accent);background-color:var(--background-accent)}
.isUnread-3Lojb- .content-3spvdd{color:var(--background-accent)}
.unreadPillCapStroke-1nE1Q8{fill:var(--background-accent);color:var(--background-accent)}
.updateIconForeground-2V_zo4{fill:var(--background-accent)}
.theme-light .title-3XlmeX{color:var(--subtext-color)}
.theme-light .subtext-2HDqJ7{color:var(--subtext-color)}
.theme-light .nameTag-sc-gpq{margin-left:-7px}
.theme-light .container-YkUktl .avatar-1EWyVD{margin-left:-5px}
.theme-light .nameTag-sc-gpq.canCopy-IgTwyV{margin-left:0}
.theme-light .subtext-2HDqJ7{color:var(--subtext-color)!important}
.theme-dark .form-2oOOG9,.theme-dark .lookFilled-1Gx00P.colorGrey-2DXtkV,.theme-dark .root-g14mjS{background-color:#191f30}
.input-m1-Y7Q{background-color:#252b3b}
.theme-dark .container-x8Y1ix{background-color:#252b3b}
.theme-dark .colorHeaderSecondary-g5teka,.theme-dark .contents-18-Yxp,.theme-dark .footerTitle-3Bslxi,.theme-dark .h5-18_1nd,.theme-dark .iconContainer-2B0ixr,.theme-dark .input-2g-os5,.theme-dark .lookFilled-1Gx00P .contents-18-Yxp,.theme-dark .lookInverted-2D7oAl .contents-18-Yxp,.theme-dark .lookLink-9FtZy- .contents-18-Yxp,.theme-dark .lookOutlined-3sRXeN .contents-18-Yxp,.theme-dark .optionHeader-27AHfD,.theme-dark .subtitle-bIoUVX,.theme-dark .subtitle-1cc8Nz,.theme-dark .subtitle-3m-md1,.theme-dark .text-PdAsFQ,.theme-dark .title-1_TkpU,.theme-dark .title-OdeD-o,.theme-dark .title-1LqMUp,.theme-dark .title-2Giw-4{color:#f3efef}
.topic-11NuQZ{-webkit-box-flex:1;-ms-flex:1 1 auto;flex:1 1 auto;max-width:600px;margin:0 0 0 8px;font-weight:500;white-space:nowrap;text-overflow:ellipsis;overflow:hidden;font-size:14px;line-height:18px;color:var(--header-secondary)}
.buttonContainer-2lnNiN{margin-right:8px}
html:root{--font-display:var(--font-primary)}
:root{--dmh-columns:3}
.unread-36eUEm{background-color:var(--background-accent);width:1.5px;height:25px;margin-top:-12px;border-radius:2px 2px 2px 2px}
.toolbar-3_r2xA a{display:none}
:root{--custom-sidebar-width:240px}
.sidebar-1tnWFu,.members-3WRCEx{width:var(--custom-sidebar-width)}
.member-2gU6Ar{max-width:var(--custom-sidebar-width)}
.contentColumnDefault-3eyv5o{max-width:unset}
.sidebarRegion-1VBisG{flex-grow:0}
.customScroller-m1-jZn>div{max-width:100%}
#app-mount .unreadMentionsIndicatorBottom-3RJMnQ{bottom:0}
.mention-1f5kbO{background-color:var(--background-accent)}
.clickable-28SzVr:hover .layout-1qmrhw,.selected-1-Z6gm .layout-1qmrhw{background-color:var(--alt-color2);border-radius:0}
.theme-dark .headerNormal-T_seeN{background-color:var(--modal-normal-primary-color);border-radius:12px 12px 0 0}
.theme-dark .body-3iLsc4,.theme-dark .footer-1fjuF6{background-color:var(--modal-normal-secondary-color);border-radius:0 0 12px 12px}
.footer-1fjuF6{display:none}
.bodyTitle-Y0qMQz{display:none}
.endBodySection-Rf4s-7{margin-bottom:15px;margin-top:2px}
.note-3HfJZ5{margin-left:-10px;height:27px;border-radius:12px}
.group-spacing-16 .divider-IqmEqJ{margin-top:10px;margin-bottom:10px}
.isUnread-3Lojb-,.unreadPill-3nEWYM{border-color:transparent;background-color:var(--background-accent)}

.container-ZMc96U{background:var(--background-primary);box-shadow:none}
#app-mount .chatContent-3KubbW .form-3gdLxP .channelTextArea-1FufC0{background-color:var(--channeltextarea-background);transition:.5s}
#app-mount .chatContent-3KubbW .form-3gdLxP .channelTextArea-1FufC0:hover{background-color:var(--channeltextarea-background-hover);filter:brightness(80%);transition:.5s}
.clickable-28SzVr:hover .layout-1qmrhw,.selected-1-Z6gm .layout-1qmrhw{transition:.25s}
.modeSelected-3DmyhH .content-1gYQeQ,.modeSelected-3DmyhH:hover .content-1gYQeQ{transition:1s}
.wrapper-NhbLHG:active .content-1gYQeQ{transition:.25s}
.button-12Fmur.enabled-9OeuTA:hover{transition:.5s}
.container-1zzFcN{border-bottom:unset}
.theme-dark .footer-31IekZ{background-color:unset!important;-webkit-box-shadow:unset;box-shadow:unset}
.theme-dark .root-g14mjS{background-color:var(--bar-background-primary)!important;-webkit-box-shadow:0 0 0 1px rgba(32,34,37,.6),0 2px 10px 0 rgba(0,0,0,.2);box-shadow:0 0 0 1px rgba(32,34,37,.6),0 2px 10px 0 rgba(0,0,0,.2)}
#app-mount .container-YkUktl{background-color:transparent;margin-left:2px}
.description-3Cwkxk{display:none}
.app-focused .isUnread-3Lojb-{border-color:var(--alt-color2)!important}
.theme-dark .headerNormal-T_seeN{background-color:var(--modal-normal-primary-color)!important;border-radius:12px 12px 0 0}
.theme-dark .body-3iLsc4,.theme-dark .footer-1fjuF6{background-color:var(--modal-normal-secondary-color)}
.app-focused .isUnread-3Lojb-{border-color:var(--alt-color2)!important}
.mentioned-Tre-dv{position:relative;background-color:var(--background-mentioned);transition:.5s}
.message-2CShn3.mentioned-Tre-dv.selected-2LX7Jy,.mouse-mode.full-motion .mentioned-Tre-dv:hover{background-color:var(--background-mentioned-hover);transition:.5s}
.wrapper-NhbLHG:hover .content-1gYQeQ{background-color:var(--background-modifier-hover);transition:.5s}
.app-focused .isUnread-3Lojb-{border-color:var(--alt-color2)!important}
.membersGroup-2eiWxl::after{content:"";display:block;width:210px;height:1px;left:7px;margin-top:4px;background:#858585;position:absolute}

.clickable-ZD7xvu:hover .icon-2xnN2Y{color:var(--interactive-hover-icons);transition:.7s}
.clickable-ZD7xvu .icon-2xnN2Y{transition:.7s}
.wrapper-3t3Yqv{background-color:var(--alt-color2);border-radius:25px;padding:0}
.wrapper-1gVUIN.normal-qRirv5{background-color:var(--background-secondary)}
.colorable-3rVGna.white-11auuQ,.colorable-3rVGna.white-11auuQ .centerIcon-JYpTUi{color:currentColor}
.wrapper-1gVUIN.minimum-fXpVNc{height:240px;background-color:var(--background-secondary);border-color:transparent!important;box-shadow:none}
.colorable-3rVGna.primary-3NQg8g,.colorable-3rVGna.primary-3NQg8g.active-3D763s,.colorable-3rVGna.primary-3NQg8g:hover,.colorable-3rVGna.white-11auuQ,.centerButton-3CaNcJ,.colorable-3rVGna.white-11auuQ.active-3D763s,.colorable-3rVGna.white-11auuQ:hover,.colorable-3rVGna.red-3T8maV{background:none!important}
.theme-dark .children-3xh0VB:after{display:none}
.actionButtons-2vEOUh .contents-18-Yxp,.inner-llGtyq{margin-left:10px;margin-top:2px}
#app-mount .sidebar-1tnWFu{border-radius:0}
.container-36u7Lw{color:var(--channels-headings)}
.icon-3zI3d2{color:var(--channels-headings)}
.selected-29KTGM .icon-2xnN2Y{color:var(--interactive-active-icons)}
.horizontal-1ae9ci{margin-left:0}
.textarea-2r0oV8:focus{background-color:transparent}
#private-channels > [class*="content-"]{display:flex;flex-wrap:wrap;align-content:flex-start;flex-direction:row}
#private-channels > [class*="content-"] > a{flex-grow:0;margin-top:8px!important}
#private-channels > [class*="content-"] > a [class*="layout-"]{justify-content:center}
#private-channels > [class*="content-"] > a [class*="avatar-"]{margin-right:0!important}
#private-channels > [class*="content-"] > a [class*="content-"]{display:none}
#private-channels > [class*="content-"] > a[href*="/channels/@me/"]{width:100%;margin-left:8px!important;margin-top:0!important}
#private-channels > [class*="content-"] > a[href*="/channels/@me/"] [class*="content-"]{display:block}
#private-channels > [class*="content-"] > a[href*="/channels/@me/"] [class*="avatar-"]{margin-right:12px!important}
#private-channels > [class*="content-"] > [aria-posinset="2"] > .layout-1qmrhw{padding-left:6px!important}
#private-channels > [class*="content-"] > [aria-posinset="3"] > .layout-1qmrhw{padding-right:0}
[aria-posinset="2"] > .layout-1qmrhw >.children-283-lq{position:absolute;bottom:-6px;right:-6px}
.colorDefault-CDqZdO{margin-right:8px}
.iconBadge-2wi9r4.iconBadge-2NuvG9.base-3IDx3L,.iconBadge-3Mmg92,.numberBadge-2s8kKX{mask:none}
.children-1MGS9G{margin-right:8px}
.containerDefault-YUSmu3,.containerDragAfter-3aBiOW,.containerDragBefore-1s5Qg6,.containerUserOver-SDa1HW{margin-left:-2px}
.messagesErrorBar-nyJGU7{background-color:var(--alt-color2);border-radius:4px;margin-bottom:2px}
.barButtonMain-3K-jeJ.barButtonBase-Sk2mdB,.barButtonAlt-mYL1lj{top:3px}
.popoutRoleDot-2_Nt5g {width: 235px;height: 35px;margin-left: -10px;border-radius: 5px;position: absolute;opacity: 0.090}

      #app-mount .container-YkUktl {
        position: unset;
        background-color: transparent;
        bottom: 0px;
        max-width: 223px;
    }
    #app-mount .sidebar-1tnWFu{
        padding-bottom: unset;
    }
    .panels-3wFtMD {
         background-color: var(--bar-background-primary);
    }
    .container-YkUktl{
        padding-top:16.5px;
        padding-bottom:16.5px;
    }
    .powercord-spotify .container-YkUktl{
         background-color: var(--bar-background-primary);
         padding-top:0px;
         padding-bottom:0px;
    }
    .powercord-spotify .spotify-buttons button{
        visibility:hidden
    }
    .powercord-spotify {
        background-color: var(--bar-background-primary);
    }
    .powercord-spotify .spotify-seek-bar{
        background-color: var(--bar-background-primary);  
    }


        #app-mount .avatarHint-k7pYop foreignObject {
          -webkit-mask: none;
                  mask: none;
        }
        .avatarHint-k7pYop {
          position: absolute;
          top: 12px;
          left: 11px;
          transform: scale(1.16);
          border-radius: var(--rs-avatar-shape);
      }
      #app-mount .wrapper-1VLyxH rect[height="24"][x="88"][y="88"] {
        width: 88% !important;
    }
div[class*="wrapper-1VLyxH"][aria-label*="Streaming"]>svg[class="mask-1FEkla svg-2azL_l"] {
  filter: drop-shadow(0 0 5px var(--rs-streaming-color));
}
[class="member-2gU6Ar offline-22aM7E container-1oeRFJ clickable-28SzVr"], div[class*="wrapper-1VLyxH"][aria-label*=""]>svg[class="mask-1FEkla svg-2azL_l"] {
  filter: drop-shadow(0 0 7px var(--rs-offline-color));
}
[class="member-2gU6Ar container-1oeRFJ clickable-28SzVr"] div[class*="wrapper-1VLyxH"]>svg[class="mask-1FEkla svg-2azL_l"] {
  filter: drop-shadow(0 0 5px var(--rs-dnd-color));
}
div[class*="wrapper-1VLyxH"][aria-label*="Idle"]>svg[class="mask-1FEkla svg-2azL_l"] {
  filter: drop-shadow(0 0 5px var(--rs-idle-color));
}
div[class*="wrapper-1VLyxH"][aria-label*="Online"]>svg[class="mask-1FEkla svg-2azL_l"] {
  filter: drop-shadow(0 0 5px var(--rs-online-color));
}
.content-1jQy2l:before {
  box-shadow: none;
}
.scrollableContainer-15eg7h::-webkit-scrollbar{
    display:none;
}
.clickable-GKg4Qy{
    background-color:black!important;
}
.avatarHint-k7pYop{
    margin-left: -5px!important;
        margin-top: -5px!important;
}

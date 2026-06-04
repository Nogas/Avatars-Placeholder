# Avatar Placeholder #
<!---
### API ###
Read more guidance in the [Document](https://avatar-placeholder.iran.liara.run/).
-->

**Generate random user profile pictures to use as placeholders for your prototypes and design projects.**
**To use the avatars in your project, use the following URLs:**

#### 1) Random avatar
```
https://avatarapi.runflare.run/public
```
<img src="https://avatarapi.runflare.run/public" width="65">

#### 2) Random boy avatar
```
https://avatarapi.runflare.run/public/boy
```
<img src="https://avatarapi.runflare.run/public/boy" width="65">

#### 3) Random girl avatar
```
https://avatarapi.runflare.run/public/girl
```
<img src="https://avatarapi.runflare.run/public/girl" width="65">

#### 4) Unique avatar by id
Where [ID] is an integer between 0 and 100.
```
https://avatarapi.runflare.run/public/[ID]
```
*example: ID=60*
<br>
<br>
<img src="https://avatarapi.runflare.run/public/60" width="65">

#### 5) Avatar based on username
###### genral
```
https://avatarapi.runflare.run/public?usearname=[value]
```
*example: usearname=Jordan*
<br>
<br>
<img src="https://avatarapi.runflare.run/public?username=Jordan" width="65">

###### boy
```
https://avatarapi.runflare.run/public/boy?usearname=[value]
```
*example: usearname=Scott*
<br>
<br>
<img src="https://avatarapi.runflare.run/public/boy?username=Scott" width="65">

###### girl
```
https://avatarapi.runflare.run/public/girl?username=[value]
```
*example: username=Angela*
<br>
<br>
<img src="https://avatarapi.runflare.run/public/girl?username=Angela" width="65">

<hr/>

### Avatars With Initials From Names
Avatars initials, also known as profile pictures with initials, are typically the first letters of a user's name displayed within an avatar icon the ability to change the background color, text color, size, etc

| Param | Type | Default | Description |
|--------|--------|---------|-------------|
| username | String (firstname + lastname) | Random * | The name used to generate initials |
| background | String (Hex Color Codes) | Random * | Background color Avatar. for example, "eeeeee". |
| color | String (Hex Color Codes) | Random * | Font color Avatar. for example, "aaaeee". |
| bold | Boolean | true | Font weight bold or not. |
| uppercase | Boolean | true | Text in Avatar image uppercase or not. |
| size | Number (Between 32 and 1024) | 256 | Avatar image size in pixels. |
| format | String (png or jpg) | png | Avatar image foramt. |
| length | Number (1 or 2) | 2 | Length of the generated initials. |

<br>

```
https://avatarapi.runflare.run/username?username=[firstname+lastname]&background=[Hex Color Codes]
```
*example: username=James+Taylor&background=f4d9b2&color=FF9800*
<br>
<br>
<img src="https://avatarapi.runflare.run/username?username=James+Taylor&background=f4d9b2&color=FF9800" width="65">
<hr/>

#### Recommended for development environments, prototypes, and non-critical applications❕
### Built by developers, for developers 👨‍💻❤️
<!--
### [Support API](https://avatar-placeholder.iran.liara.run/donate) ###
your support ensures our API’s long and happy life. Devs and businesses relying on it will thank you. Thanks for being part of our digital adventure! 😊
-->

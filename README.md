# OIDC-Configuration-with-cognito-user-pool
![1](https://user-images.githubusercontent.com/64592542/171078376-6aa39ca4-17e9-4fa5-94e1-6d7b94b453a2.png)
![2](https://user-images.githubusercontent.com/64592542/171078409-7dfa3a2c-4c7e-4104-a75c-86400b29a074.png)
![3](https://user-images.githubusercontent.com/64592542/171078451-3ce635c4-1f55-4ee7-88a5-db716f6a5a08.png)
![4](https://user-images.githubusercontent.com/64592542/171078546-d99d2032-6e80-42de-aecc-78cd6b43d7c1.png)
![5](https://user-images.githubusercontent.com/64592542/171078559-f5246d8d-79d8-47b2-8ffd-ba14577a2120.png)
![6](https://user-images.githubusercontent.com/64592542/171078572-fd56208c-4807-427a-9871-2d31e8741b60.png)
![7](https://user-images.githubusercontent.com/64592542/171078597-691440a7-1fe5-40fe-9ed6-2fa924fbbf05.png)
![8](https://user-images.githubusercontent.com/64592542/171078633-04569bed-658a-4793-94ce-a6861c705eb4.png)
![9](https://user-images.githubusercontent.com/64592542/171078644-2c3a5c9f-eb5b-4532-921f-dee4f73cc502.png)
![10](https://user-images.githubusercontent.com/64592542/171078656-20ddf587-8298-48fa-9a59-801d572c92f9.png)
![11](https://user-images.githubusercontent.com/64592542/171078661-a81d2d33-0703-42be-bdde-2b8b2d88c21c.png)
![12](https://user-images.githubusercontent.com/64592542/171078674-d349e78d-d27f-4e25-a32e-a25bac851e66.png)
![13](https://user-images.githubusercontent.com/64592542/171078693-2672b9bf-2c31-4241-99c5-4aea16781f46.png)
![14](https://user-images.githubusercontent.com/64592542/171078706-b8d50887-8752-4071-b4b7-518a8d92292c.png)
![15](https://user-images.githubusercontent.com/64592542/171078718-f375ace9-4e1e-463a-ad24-70b635a1cc3e.png)
![16](https://user-images.githubusercontent.com/64592542/171078733-4d0ec975-4450-436c-bd02-74136272c943.png)
....................................................................................................................
Go to OpenID Connect Configuration
link: https://openidconnect.net/

![Screenshot (21)](https://user-images.githubusercontent.com/64592542/171079267-415425ee-99f3-46a7-b377-119a16202218.png)
copy this link    https://openidconnect.net/callback  and put herte ![Screenshot (23)](https://user-images.githubusercontent.com/64592542/171079460-413343d4-f330-47d7-b99e-eb660d94d75f.png)

GO TO configuration button 
![Screenshot (25)](https://user-images.githubusercontent.com/64592542/171079815-67288c7e-4e7b-4eb1-af97-ee7c0ccd0b17.png)




![Screenshot (26)](https://user-images.githubusercontent.com/64592542/171079918-1b4435a9-0d6f-4a67-a6d7-48f2eb5fe78b.png)

only chnage
Server Template = custome
Discovery Document URL = https://cognito-idp.us-east-1.amazonaws.com/us-east-1_3S1Jp1dfR/.well-known/openid-configuration
 
 default value  = https://cognito-idp.us-east-1.amazonaws.com
 poolid  = us-east-1_3S1Jp1dfR
 default value    .well-known/openid-configuration
 
 copy link and paste in url box check working or not 
 https://cognito-idp.us-east-1.amazonaws.com/us-east-1_3S1Jp1dfR/.well-known/openid-configuration
 
 output 
 ![Screenshot (30)](https://user-images.githubusercontent.com/64592542/171081077-a5b45597-9858-4e23-98eb-19a2acf62398.png)

 
 
 then click use discovery document 
 
 
 ![Screenshot (29)](https://user-images.githubusercontent.com/64592542/171080797-c8ddf6bd-c6fa-4f0e-befd-185eea9602b9.png)

 OIDC Client ID  replace by aws App client id 
 OIDC Client Secret replace by aws App client secret
 
 
 
 Scope exactly same Allowed OAuth Scopes
 ![Screenshot (32)](https://user-images.githubusercontent.com/64592542/171081413-15056086-675f-4c1d-8dee-f52120a38a2c.png)
 ![Screenshot (33)](https://user-images.githubusercontent.com/64592542/171081485-4e98c7a2-37ea-4166-b131-97327dd783de.png)
 
 
 and save 
 Redirect to OpenID Connect Server => start  exchange next  varify 
 
 

 

 



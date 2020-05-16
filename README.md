# Image Classification Restful API

<h2>Restful API for similarity check using natural language processing</h2>
{The application includes Docker and written in Python}<br>

- Each user can register and create an accout <br>
- All Data information is storred in MongoDB <br>
- No need to build front-end -> it can be tested via Postman <br>
- Each User has tokens to be used to classify an image <br>
- Only Admin is allowed to add tokens to users <br>
- Using TernserFlow (Import frmo NumPy) to classify images <br>
- Using bcrypt to encrypt passwords <br>
 <br>
<h4>The restful apis are (All POST):</h4>
/register/{username}/{password} (To register a user) <br>
/classify/{username}/{password}/{image-url} <br>
/refill/{user-username}/{admin-password}/{number-of-token} <br>

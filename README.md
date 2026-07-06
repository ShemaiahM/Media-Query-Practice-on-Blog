# Media-Query-Practice-on-Blog
link to website:https://basicblogmediaquery1.netlify.app/

## What was achieved 
- Use of Media query, Changing the website size to fit screens in mobile first and web responsive design.
- Here is a snippet of the @media query for the mobile, there was little changes to the article class card(utility class).
- 
- `/* mobile */
@media only screen and (min-width: 100px) and (max-width: 399px) {
  /* card */
  .card {
    border: 2px solid black;
    overflow: hidden;
    width: 120px;
    margin: 10px;
    border-radius: 10px;
    box-shadow: 0px 4px 8px #555;
    transition: transform 250ms;

    & img {
      width: 100%;
      object-fit: cover;
    }
  }
  .card-contents {
    padding: 10px;
    text-align: center;
  }
  .card:hover {
    transform: translateY(-10px);
  }

  .about {
    display: flex;
    justify-content: space-evenly;
    padding: 10px;
    gap: 10px;
    border: 1px solid red;
    flex-wrap: wrap;
  }
}`

#### Conclusion
- Will need fiurther more practice and exploration of such. Im still having ussues with flex:1; yet will continue to practice such, everything else is straightforward.

### Normal alyop screen
<img width="917" height="682" alt="image" src="https://github.com/user-attachments/assets/47f5feff-0e8b-4afe-a0a9-145b53f98066" />


### Ipad Mini display
<img width="851" height="675" alt="image" src="https://github.com/user-attachments/assets/1c65e65a-c4ef-4405-8e42-b2483cd290e2" />


### Iphone 12 Pro
<img width="1015" height="687" alt="image" src="https://github.com/user-attachments/assets/287d5746-0f14-488c-9a46-0edb25bee959" />

### Iphone 14 Pro  Max
<img width="1012" height="680" alt="image" src="https://github.com/user-attachments/assets/76bdb220-db47-42f9-87f3-f3e9532b84eb" />

### Samsung S20 Ultra

<img width="1017" height="682" alt="image" src="https://github.com/user-attachments/assets/0c0239b6-2a9f-41fc-a4e0-50387a199fc8" /> <img width="1017" height="682" alt="image" src="https://github.com/user-attachments/assets/fb6c6839-8b79-427c-aa45-0f5e7afee178" />

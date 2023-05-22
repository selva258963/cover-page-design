# cover-page-design
AIM:
To develop a website to display the cover page design of a book

Design Steps:
Step 1:
Clone into the repository named 'cover-page-design' and create a django admin interface.

Step 2:
Write HTML and CSS code for designing book cover page and excute them

## Code:
cover.html:

<!DOCTYPE html>
<html lang="en">
    <head>
        <title>HOW TO BECOME RICH IN 1 DAY</title>
        <style>
        h1{
           color:white;
        }
         .bookpage{
             width: 400px;
             height: 650px;
             background-color: black;
             background-position: center;
             margin-left: auto;
             margin-right: auto ;
             padding: 20px;
             background-image: url("v.jpeg");
             background-size: cover;
             background-repeat: no-repeat;

         }
         .toptext{
             color:white;
             padding-left: 10px;
             font-size: 14px;
             font-family: Arial, Helvetica, sans-serif;

         }
         .tophr{
             color:#e36f2f;
              width: 180px;
         }
         hr{
             color:#e36f2f;

         }
         .booktitle{
             font-family: Arial, Helvetica, sans-serif;
             padding: 10px 10px 0px 10px;
             display: flex;
            align-items: center;
            justify-content: center;
  margin-right: 10px;
  margin-left: 10px;
  font-size: 20px;
         }
         .author{
             color:white;
             font-family: Arial, Helvetica, sans-serif;
             display: inline;
             font-size: 24px;
             position:relative;
             line-height: 20px;


         }
         .sub-text {
             color:white;
             font-family: Arial, Helvetica, sans-serif;
             display: flex;
             line-height: 5px;

  margin-right: 10px;
  margin-left: 10px;

  font-size: 14px;
  }

.footer {
  color:orange;
  padding-top: 180px;
}
.image {
    color:white;
             font-family: Arial, Helvetica, sans-serif;
 font-size: 22px;
  margin-right: 20px;
}
.bottomhr {
    color:#e36f2f;
              width: 400px;

}
img {
    width: 90px;
    height: 100px;
    margin-right: 20px;
    vertical-align: bottom;
}
.edition {
    color:#e36f2f;
             font-family: Arial, Helvetica, sans-serif;
 font-size: 22px;
 line-height:bottom;

}


        </style>
        </head>
            <body>
                <div class="bookpage">

                    <div class="toptext">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;BEGINNER FRIENDLY</div>
                    <div class="tophr"><hr></div>
               <div class="booktitle"><h1>EASY WAY TO BECOME RICH</h1></div>
               <h3 class="sub-text">HOW TO BECOME RICH IN 1 DAY</h3>
                    <h3 class="sub-text">written by SELVAMUTHU KUMARAN</h3>
                    <div class="footer">
                        <h2 class="edition">&nbsp;&nbsp;First
Edition&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  <img src="IMG-20221207-WA0017.jpg" alt="Author"></h2>

                        <div class="bottomhr"><hr></div>
                    <div class="author"><h3>&nbsp;&nbsp;Selva &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</h3></div>

                </div>
                </div>

            </body>


</html>
## Output:
![Screenshot (26)](https://github.com/selva258963/cover-page-design/assets/121961701/54e16f83-add7-4cec-9a7b-5a182de4fd1a)


## Result:
code is successfully exicuted

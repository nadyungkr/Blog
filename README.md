# Portpolio BLOG 형식

> 열심히 작성한 코드가 겨우 한줄 밖에 나가지 못했어도 나는 포기하지 않는다.

## SLIDE bar가 왼쪽에 있는 간단하고 미니멀한 블로그 형식 홈페이지 만들기


1. position:fixed를 사용한다  
````html
<!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="utf-8">
        <title>세로 메뉴 만들기</title>
    <style>
        .sidebar {
            position:fixed;
            width:280px;
            overflow-x:hidden;
            overflow-y:scroll;
            /*overflow-y:auto; 도 가능*/
            height:100%;
            background:#fff;
            outline:1px solid red;
        }
    </style>
    </head>
    <body>
        <div class="slidebar">
            <div class="profilecard">
            <nav>
                <ul>
                    <li>주메뉴</li>
                    <li>주메뉴</li>
                    <li>주메뉴</li>
                </ul>
            </nav>
            </div>
        </div>
    </body>
    </html>
````


## 미니블로그 레이아웃을 보고 싶다면?

1. clone하여 로컬저장소에 파일을 전송하거나 download.zip 을 이용한다.  
    (You have to clone or download.zip)
2. <index.html> 파일을 클릭한다.  
    *repository folder open* Click <index.html>

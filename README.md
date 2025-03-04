<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <title>用户注册</title>
</head>
<body>
    <form>
        <h1>用户注册</h1>
        <label for="username">用户名：</label>
        <input type="text" id="username" name="username" value="zhangsan"><br><br>
        
        <label for="password">用户密码：</label>
        <input type="password" id="password" name="password"><br><br>
        
        <label>用户性别：</label>
        <input type="radio" id="male" name="gender" value="male" checked>
        <label for="male">男</label>
        <input type="radio" id="female" name="gender" value="female">
        <label for="female">女</label><br><br>
        
        <label>爱好：</label>
        <input type="checkbox" id="football" name="hobby" value="足球">
        <label for="football">足球</label>
        <input type="checkbox" id="basketball" name="hobby" value="篮球">
        <label for="basketball">篮球</label>
        <input type="checkbox" id="lol" name="hobby" value="LOL">
        <label for="lol">LOL</label>
        <input type="checkbox" id="koreanDrama" name="hobby" value="韩剧">
        <label for="koreanDrama">韩剧</label>
        <input type="checkbox" id="kingOfGlory" name="hobby" value="王者荣耀">
        <label for="kingOfGlory">王者荣耀</label><br><br>
        
        <label for="email">邮箱：</label>
        <input type="email" id="email" name="email" placeholder="请输入您的邮箱"><br><br>
        
        <label for="avatar">用户头像：</label>
        <input type="file" id="avatar" name="avatar"><br><br>
        
        <label for="address">您的家庭住址是：</label>
        <select id="address" name="address">
            <option value="陕西">陕西</option>
            <!-- 其他省份选项 -->
        </select><br><br>
        
        <label for="suggestions">您的建议或者意见</label><br>
        <textarea id="suggestions" name="suggestions" rows="4" cols="50">您的建议 或者 意见</textarea><br><br>
    </form>
</body>
</html>

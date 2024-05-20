document.addEventListener('DOMContentLoaded', function() {
    var submitButton = document.getElementById('submit');
    if (submitButton) {
        submitButton.addEventListener('click', function(event) {
            event.preventDefault();
            var username = document.getElementById('username').value;
            var password = document.getElementById('password').value;
            AV.User.logIn(username, password).then((user) => {
                // 隐藏登录框
                document.querySelector('.test1').style.display = 'none';
                document.querySelector('.test2').style.display = 'none';

                // 获取URL链接并显示
                var urls = [user.get('url_1'), user.get('url_2')];
                var linksList = document.getElementById('links-list');
                var index_item = ['[Download Methods 1]: Download from Tianchi (Recommand!!!)\n','[Download Methods 2]: Download from Baidu driver (Finally, you need to submit your csv files in Tianchi)']
                urls.forEach(function(url, index) {
                    var listItem = document.createElement('li');
                    var link = document.createElement('a');
                    link.href = url;
                    link.textContent =  index_item[index];
                    listItem.appendChild(link);
                    linksList.appendChild(listItem);
                });

                // 显示链接容器
                document.getElementById('links-container').style.display = 'block';
            }).catch(function(error) {
                console.error('Login failed', error);
            });
        });
    }
});

// 初始化
AV.init({
    appId: "j8824Hf9e50X6YCJwTTuci49-gzGzoHsz",
    appKey: "PBbh6gzWJQ188mA8A76fYSZA",
    serverURLs: "https://j8824hf9.lc-cn-n1-shared.com"
});

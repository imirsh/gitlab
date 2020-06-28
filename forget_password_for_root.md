在root用户下，执行：`~]# gitlab-rails console  -e production`
- `:002:0>  user = User.where(id: 1).first`
- `003:0> user.password="12345678"`
- `004:0> user.password_confirmation="12345678"`
- `:005:0>  user.save!`
- `:006:0>  quit`

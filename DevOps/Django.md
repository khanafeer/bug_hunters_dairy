django common commands

```python
django-admin startproject mysite

```

password reset

```python
from django.contrib.auth.models import User
u = User.objects.get(username__exact='admin')
u.set_password('123456789')
u.save()
```


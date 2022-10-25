# mirror
Mirror container registry repository for common container images

My dear Iranian friends, this repository is made as a mirror for common Docker images that are not available from Docker Hub for Iranian users due to geographical restrictions.
The images are based on the official images, with no change. You can see the Containerfiles. They are very simple.

# رجیستری آینه برای ایمیج‌های پرکاربرد داکر

ایمیج‌های داکر به علت محدودیت‌های جغرافیایی برای کاربران ایرانی در دسترس نیستند.
این ریپوزیتوری برای دور زدن این مشکل ایجاد شده است.
ایمیج‌های موجود در این ریپوزیتوری عینا همان ایمیج‌های داکر هستند و هیچ تغییری در آن‌ها داده نشده است.
شما می‌توانید فایل‌های کانتینر موجود را مشاهده کنید. آنها بسیار ساده هستند.

## How to Pull Images (نحوه دریافت ایمیج‌ها)

Pull the images with Podman or Docker CLI in the following form:

```

podman pull ghcr.io/djnotes/image-name:latest

```
For example, to pull alpine, simple run the following command: 
```
podman pull ghcr.io/djnotes/alpine:latest
```
Or with docker:
```
docker pull ghcr.io/djnotes/alpine:latest
```


## List of Images:
- Adminer
- Alpine
- Apache
- Busybox
- Debian
- HTTPD
- MariaDB
- MongoDB
- NGINX
- Node
- PHP (with Apache)
- Postgres
- Python
- RabbitMQ
- Redis
- Ruby
- Traefik
- Ubuntu
- WordPress
- Composer


## Want More Images?

If you need an image included, feel free to open an issue or send a pull request!
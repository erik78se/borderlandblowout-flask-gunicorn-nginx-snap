# flask-config

This is a bare bones example of snapping a flask application with dynamic config.

```bash
git clone git@github.com:jamesbeedy/simple-flask-gunicorn-nginx-snap.git

cd simple-flask-gunicorn-nginx-snap

sudo snapcraft -d

sudo snap install flask-nginx_0.1_amd64.snap --devmode
```

Then open up http://<ipaddress-where-snap-is-running>:9999 in your browser.


You should be able to view the snap logs with
```bash
sudo journalctl -u snap.flask-nginx.flask-nginx.service
```

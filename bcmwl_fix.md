# Steps to fix the bcmwl-kernel-source failed to build on kernel 5.8

```bash
sudo apt remove --auto-remove bcmwl-kernel-source && \
sudo apt purge --auto-remove bcmwl-kernel-source
wget http://archive.ubuntu.com/ubuntu/pool/restricted/b/bcmwl/bcmwl-kernel-source_6.30.223.271+bdcom-0ubuntu7_amd64.deb
sudo dpkg -i bcmwl-kernel-source_6.30.223.271+bdcom-0ubuntu7_amd64.deb
```




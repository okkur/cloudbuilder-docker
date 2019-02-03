### docker-make
An alpine based image that includes docker and make

### Usage
Add this step to your cloud build config
```yaml
- name: 'gcr.io/erfanb-223517/docker-make'
  args: ['docker-build']
```
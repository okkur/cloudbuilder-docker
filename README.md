### docker-make
An alpine based image that includes docker and make

### Usage
Add this step to your cloud build config
```yaml
- name: 'gcr.io/okkur-230615/docker-make'
  args: ['build']
```
# ytt-springboot
Spring boot configuration (`application.yaml`) using ytt

## Prerequisites
- [ytt](https://carvel.dev/ytt/docs/latest/)
```
brew tap carvel-dev/carvel
brew install ytt
```

## Usage
- To render the configuration
```
ytt -f application-dev.yaml -f common
```

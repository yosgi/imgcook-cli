# imgcook-cli

imgcook-cli can combine the capabilities of Plugin to place the code products generated by the imgcook platform into your local project project, and seamlessly integrate into your development process. Upload pictures to your own bed, file directory conversion, etc.), imgcook-cli is a very good choice for you.

## Getting Started
## Install
> The imgcook-cli installation depends on Node.js and NPM. It is recommended to use Node.js version 9.x


```shell
# npm
npm install -g @imgcook/cli
# yarn
yarn global add @imgcook/cli
```

## Use


### Common command

#### imgcook config
>  User settings configuration, default initialization generates official configuration


```shell
# Setting config
imgcook config set

#  View config
imgcook config ls

# Open configuration file directly
imgcook config edit
```

> DSL config：
> React D2C Schema：41
> Vue 开发规范：29
> 微信小程序开发规范：21
> React 开发规范：12
> H5 标准开发规范：5
> Rax 标准开发规范：1
> 
> Get accessId ：Official website top right corner avatar -> Personal page -> Top left Icon
> ![image.png](https://intranetproxy.alipay.com/skylark/lark/0/2019/png/199/1576161013370-acd72bac-c714-4653-828e-963d6aea3c8b.png#align=left&display=inline&height=164&name=image.png&originHeight=480&originWidth=1156&size=151842&status=done&style=none&width=396)


#### imgcook pull
> Pull module code


```shell
# Pull a module code to a local path
imgcook pull <moduleId> --path <path>
# Example
imgcook pull 17108 --path mod
```

#### imgcook install
> Plugins required to install imgcook-cli


```shell
# Install all configured plugins by default
imgcook install

# Install the specified plugin
imgcook install plugin --name <value>

# Example
imgcook install plugin --name @imgcook/plugin-images
```

### Options

#### imgcook --version
> Display version information


```shell
imgcook --version
imgcook -v
```

#### imgcook --help
> Show command usage help


```shell
imgcook --help
imgcook -h
```

## License
[MIT](https://github.com/imgcook/imgcook-cli/blob/master/LICENSE)
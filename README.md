# ETH dsk [中文](./README_CN.md) #

[![Build Status](https://travis-ci.org/nacos-group/nacos-sdk-go.svg?branch=master)](https://travis-ci.org/nacos-group/nacos-sdk-go) [![Go Report Card](https://goreportcard.com/badge/github.com/nacos-group/nacos-sdk-go)](https://goreportcard.com/report/github.com/nacos-group/nacos-sdk-go) ![license](https://img.shields.io/badge/license-Apache--2.0-green.svg)

---

## Nacos-sdk-go

sdk说明

## Requirements

支持的go版本号

## Installation
Use `go get` to install SDK：
```sh
$ 
```
## 示例
* ClientConfig

```go

// 实例结构体
type sdk struct {}

// 传参结构体
type params struct {}

// 响应机构体
type response struct {}

// 请求结构体
type request struct {}

// 配置结构体
type config struct {}


```

### 初始化

```go

	// 实例化方式 1

	// 传参方式1 通过map传参实例化
	sdk := sdk.New(map[string]string{"id": "1", "url": "http://localhost:3336"})

	// 传参方式2 通过结构体传参实例化
	sdk.params{}
	sdk := sdk.ProtocolVersion(params)

	// 调用方式 实例.方法
	sdk.Params{}
	result := sdk.ProtocolVersion(sdk)

	// 目录结构
	/test									测试
	/example							实例
	/util									工具类
	/rpc									rpc核心文件
		/response						处理响应
		/request						处理请求
		/block							处理区块业务
		/trade							处理交易业务
		/error							异常处理
	/config								配置文件



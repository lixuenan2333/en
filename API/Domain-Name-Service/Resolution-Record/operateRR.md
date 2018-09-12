# operateRR


## 描述
Enable, disable, delete the resolution records under the main domain name

## 请求方式
POST

## 请求地址
https://clouddnsservice.jdcloud-api.com/v1/regions/{regionId}/domain/{domainId}/RROperate

|名称|类型|是否必需|默认值|描述|
|---|---|---|---|---|
|**domainId**|String|True||Domain Name ID|
|**regionId**|String|True||Region ID to which the instance belongs|

## 请求参数
|名称|类型|是否必需|默认值|描述|
|---|---|---|---|---|
|**action**|String|True||Operation type, on->enable, off->disable, del->delete|
|**ids**|Integer[]|True||Resolution record ID of the operation demanded|


## 返回参数
|名称|类型|描述|
|---|---|---|
|**requestId**|String|ID of this request|



## 返回码
|返回码|描述|
|---|---|
|**200**|OK|
|**400**|BAD_REQUEST|
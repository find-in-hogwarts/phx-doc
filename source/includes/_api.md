
 <h1 class="curproject-name"> x-trade-openapi </h1> 
 


# webApi 资金

## 切换保证金模式
<a id=切换保证金模式2699> </a>
### 基本信息

**Path：** /v1/trade/web/switch/marginType

**Method：** POST

**接口描述：**
<p></p>

### 请求参数
**Headers**

| 参数名称  | 参数值  |  是否必须 | 示例  | 备注  |
| ------------ | ------------ | ------------ | ------------ | ------------ |
| Content-Type  |  application/json | 是  |  application/json |   |
**Body**

<table>
  <thead class="ant-table-thead">
    <tr>
      <th key=name>名称</th><th key=type>类型</th><th key=required>是否必须</th><th key=default>默认值</th><th key=desc>备注</th><th key=sub>其他信息</th>
    </tr>
  </thead><tbody className="ant-table-tbody"><tr key=0-0><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> tradeType</span></td><td key=1><span>string</span></td><td key=2>必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">业务线</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>linearPerpetual</span></p></td></tr><tr key=0-1><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> symbol</span></td><td key=1><span>string</span></td><td key=2>必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">交易对</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>BTCUSDT</span></p></td></tr><tr key=0-2><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> marginType</span></td><td key=1><span>string</span></td><td key=2>必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">交易模式：保证金模式：isolated：逐仓 ；cross：全仓</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>cross</span></p></td></tr>
               </tbody>
              </table>
            
### 返回数据

<table>
  <thead class="ant-table-thead">
    <tr>
      <th key=name>名称</th><th key=type>类型</th><th key=required>是否必须</th><th key=default>默认值</th><th key=desc>备注</th><th key=sub>其他信息</th>
    </tr>
  </thead><tbody className="ant-table-tbody"><tr key=0-0><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> msg</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">请求结果描述。请求成功返回成功描述。发生错误返回具体错误描述。</span></td><td key=5></td></tr><tr key=0-1><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> data</span></td><td key=1><span>object</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">数据</span></td><td key=5></td></tr><tr key=0-1-0><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> tradeType</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">业务线</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>linearPerpetual</span></p></td></tr><tr key=0-1-1><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> symbol</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">交易对</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>BTCUSDT</span></p></td></tr><tr key=0-1-2><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> marginType</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">交易模式：保证金模式：isolated：逐仓 ；cross：全仓</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>cross</span></p></td></tr><tr key=0-2><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> code</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">错误码</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1</span></p></td></tr><tr key=0-3><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> ts</span></td><td key=1><span>integer</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">系统时间</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1660101471921</span></p></td></tr><tr key=0-4><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> traceId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr>
               </tbody>
              </table>
            
## 获取保证金模式
<a id=获取保证金模式2699> </a>
### 基本信息

**Path：** /v1/trade/web/query/marginType

**Method：** GET

**接口描述：**
<p></p>

### 请求参数
**Query**

| 参数名称  |  是否必须 | 示例  | 备注  |
| ------------ | ------------ | ------------ | ------------ |
| tradeType | 是  |   |  业务线 |
| symbol | 是  |   |  交易对 |

### 返回数据

<table>
  <thead class="ant-table-thead">
    <tr>
      <th key=name>名称</th><th key=type>类型</th><th key=required>是否必须</th><th key=default>默认值</th><th key=desc>备注</th><th key=sub>其他信息</th>
    </tr>
  </thead><tbody className="ant-table-tbody"><tr key=0-0><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> msg</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">请求结果描述。请求成功返回成功描述。发生错误返回具体错误描述。</span></td><td key=5></td></tr><tr key=0-1><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> data</span></td><td key=1><span>object</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">数据</span></td><td key=5></td></tr><tr key=0-1-0><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> tradeType</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">业务线</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>linearPerpetual</span></p></td></tr><tr key=0-1-1><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> symbol</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">交易对</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>BTCUSDT</span></p></td></tr><tr key=0-1-2><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> marginType</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">交易模式：保证金模式：isolated：逐仓 ；cross：全仓</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>cross</span></p></td></tr><tr key=0-2><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> code</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">错误码</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1</span></p></td></tr><tr key=0-3><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> ts</span></td><td key=1><span>integer</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">系统时间</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1660101471921</span></p></td></tr><tr key=0-4><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> traceId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr>
               </tbody>
              </table>
            
## 资金查询接口
<a id=资金查询接口2699> </a>
### 基本信息

**Path：** /v1/trade/web/tradingAccount

**Method：** GET

**接口描述：**
<p></p>

### 请求参数
**Query**

| 参数名称  |  是否必须 | 示例  | 备注  |
| ------------ | ------------ | ------------ | ------------ |
| currency | 否  |   |  币种 |

### 返回数据

<table>
  <thead class="ant-table-thead">
    <tr>
      <th key=name>名称</th><th key=type>类型</th><th key=required>是否必须</th><th key=default>默认值</th><th key=desc>备注</th><th key=sub>其他信息</th>
    </tr>
  </thead><tbody className="ant-table-tbody"><tr key=0-0><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> msg</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">请求结果描述。请求成功返回成功描述。发生错误返回具体错误描述。</span></td><td key=5></td></tr><tr key=0-1><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> data</span></td><td key=1><span>object []</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">数据</span></td><td key=5><p key=3><span style="font-weight: '700'">item 类型: </span><span>object</span></p></td></tr><tr key=0-1-0><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> currency</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">币种</span></td><td key=5></td></tr><tr key=0-1-1><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> marginEquity</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">总资产(账户权益)</span></td><td key=5></td></tr><tr key=0-1-2><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> marginAvailable</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">可用保证金</span></td><td key=5></td></tr><tr key=0-1-3><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> marginFrozen</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">冻结保证金</span></td><td key=5></td></tr><tr key=0-1-4><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> maxWithdrawAmount</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">最大可转出余额</span></td><td key=5></td></tr><tr key=0-1-5><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> marginPosition</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">持仓保证金（当前持有仓位所占用的保证金）</span></td><td key=5></td></tr><tr key=0-1-6><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> balance</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">账户余额</span></td><td key=5></td></tr><tr key=0-1-7><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> profitUnreal</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">未实现盈亏</span></td><td key=5></td></tr><tr key=0-1-8><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> maintenanceMargin</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">维持保证金</span></td><td key=5></td></tr><tr key=0-1-9><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> marginRate</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">保证金比率</span></td><td key=5></td></tr><tr key=0-2><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> code</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">错误码</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1</span></p></td></tr><tr key=0-3><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> ts</span></td><td key=1><span>integer</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">系统时间</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1660101471921</span></p></td></tr><tr key=0-4><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> traceId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr>
               </tbody>
              </table>
            
# webApi 杠杆

## 切换杠杆
<a id=切换杠杆2704> </a>
### 基本信息

**Path：** /v1/trade/web/leverage

**Method：** POST

**接口描述：**
<p></p>

### 请求参数
**Headers**

| 参数名称  | 参数值  |  是否必须 | 示例  | 备注  |
| ------------ | ------------ | ------------ | ------------ | ------------ |
| Content-Type  |  application/json | 是  |  application/json |   |
**Body**

<table>
  <thead class="ant-table-thead">
    <tr>
      <th key=name>名称</th><th key=type>类型</th><th key=required>是否必须</th><th key=default>默认值</th><th key=desc>备注</th><th key=sub>其他信息</th>
    </tr>
  </thead><tbody className="ant-table-tbody"><tr key=0-0><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> tradeType</span></td><td key=1><span>string</span></td><td key=2>必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">业务线</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>linearPerpetual</span></p></td></tr><tr key=0-1><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> symbol</span></td><td key=1><span>string</span></td><td key=2>必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">交易对</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>BTCUSDT</span></p></td></tr><tr key=0-2><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> leverage</span></td><td key=1><span>string</span></td><td key=2>必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">杠杆倍数</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>10</span></p></td></tr><tr key=0-3><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> marginType</span></td><td key=1><span>string</span></td><td key=2>必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">交易模式：保证金模式：isolated：逐仓 ；cross：全仓</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>cross</span></p></td></tr>
               </tbody>
              </table>
            
### 返回数据

<table>
  <thead class="ant-table-thead">
    <tr>
      <th key=name>名称</th><th key=type>类型</th><th key=required>是否必须</th><th key=default>默认值</th><th key=desc>备注</th><th key=sub>其他信息</th>
    </tr>
  </thead><tbody className="ant-table-tbody"><tr key=0-0><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> msg</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">请求结果描述。请求成功返回成功描述。发生错误返回具体错误描述。</span></td><td key=5></td></tr><tr key=0-1><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> data</span></td><td key=1><span>object</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">数据</span></td><td key=5></td></tr><tr key=0-1-0><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> tradeType</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">交易类型，正向永续：linearPerpetual，币本位:inversePerpetual--先定义永续</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>linearPerpetual</span></p></td></tr><tr key=0-1-1><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> symbol</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">交易对</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>BTCUSDT</span></p></td></tr><tr key=0-1-2><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> leverage</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">杠杆倍数</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>10</span></p></td></tr><tr key=0-1-3><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> marginType</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">交易模式：保证金模式：isolated：逐仓 ；cross：全仓</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>cross</span></p></td></tr><tr key=0-2><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> code</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">错误码</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1</span></p></td></tr><tr key=0-3><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> ts</span></td><td key=1><span>integer</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">系统时间</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1660101471921</span></p></td></tr><tr key=0-4><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> traceId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr>
               </tbody>
              </table>
            
## 获取用户当前杠杆
<a id=获取用户当前杠杆2704> </a>
### 基本信息

**Path：** /v1/trade/web/leverage/info

**Method：** GET

**接口描述：**
<p></p>

### 请求参数
**Query**

| 参数名称  |  是否必须 | 示例  | 备注  |
| ------------ | ------------ | ------------ | ------------ |
| tradeType | 是  |   |  业务线 |
| symbol | 是  |   |  交易对 |
| marginType | 否  |   |  交易模式：保证金模式：isolated：逐仓 ；cross：全仓 |

### 返回数据

<table>
  <thead class="ant-table-thead">
    <tr>
      <th key=name>名称</th><th key=type>类型</th><th key=required>是否必须</th><th key=default>默认值</th><th key=desc>备注</th><th key=sub>其他信息</th>
    </tr>
  </thead><tbody className="ant-table-tbody"><tr key=0-0><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> msg</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">请求结果描述。请求成功返回成功描述。发生错误返回具体错误描述。</span></td><td key=5></td></tr><tr key=0-1><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> data</span></td><td key=1><span>object []</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">数据</span></td><td key=5><p key=3><span style="font-weight: '700'">item 类型: </span><span>object</span></p></td></tr><tr key=0-1-0><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> tradeType</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">交易类型，正向永续：linearPerpetual，币本位:inversePerpetual--先定义永续</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>linearPerpetual</span></p></td></tr><tr key=0-1-1><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> symbol</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">交易对</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>BTCUSDT</span></p></td></tr><tr key=0-1-2><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> leverage</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">杠杆倍数</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>10</span></p></td></tr><tr key=0-1-3><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> marginType</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">交易模式：保证金模式：isolated：逐仓 ；cross：全仓</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>cross</span></p></td></tr><tr key=0-2><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> code</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">错误码</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1</span></p></td></tr><tr key=0-3><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> ts</span></td><td key=1><span>integer</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">系统时间</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1660101471921</span></p></td></tr><tr key=0-4><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> traceId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr>
               </tbody>
              </table>
            
# webApi 订单

## 一键平仓
<a id=一键平仓2709> </a>
### 基本信息

**Path：** /v1/trade/web/oneClickClose

**Method：** POST

**接口描述：**
<p></p>

### 请求参数
**Headers**

| 参数名称  | 参数值  |  是否必须 | 示例  | 备注  |
| ------------ | ------------ | ------------ | ------------ | ------------ |
| Content-Type  |  application/json | 是  |  application/json |   |
**Body**

<table>
  <thead class="ant-table-thead">
    <tr>
      <th key=name>名称</th><th key=type>类型</th><th key=required>是否必须</th><th key=default>默认值</th><th key=desc>备注</th><th key=sub>其他信息</th>
    </tr>
  </thead><tbody className="ant-table-tbody"><tr key=0-0><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> tradeType</span></td><td key=1><span>string</span></td><td key=2>必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">交易类型，正向合约：linearPerpetual</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>linearPerpetual</span></p></td></tr><tr key=0-1><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> symbol</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">交易对。常用形式为“基础货币”+“报价货币”</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>BTCUSDT</span></p></td></tr>
               </tbody>
              </table>
            
### 返回数据

<table>
  <thead class="ant-table-thead">
    <tr>
      <th key=name>名称</th><th key=type>类型</th><th key=required>是否必须</th><th key=default>默认值</th><th key=desc>备注</th><th key=sub>其他信息</th>
    </tr>
  </thead><tbody className="ant-table-tbody"><tr key=0-0><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> msg</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">请求结果描述。请求成功返回成功描述。发生错误返回具体错误描述。</span></td><td key=5></td></tr><tr key=0-1><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> data</span></td><td key=1><span>object []</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">数据</span></td><td key=5><p key=3><span style="font-weight: '700'">item 类型: </span><span>object</span></p></td></tr><tr key=0-1-0><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> orderId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">订单号</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>12345678901234567890</span></p></td></tr><tr key=0-1-1><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> createTime</span></td><td key=1><span>integer</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">创建时间</span></td><td key=5></td></tr><tr key=0-2><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> code</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">错误码</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1</span></p></td></tr><tr key=0-3><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> ts</span></td><td key=1><span>integer</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">系统时间</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1660101471921</span></p></td></tr><tr key=0-4><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> traceId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr>
               </tbody>
              </table>
            
## 一键撤单
<a id=一键撤单2709> </a>
### 基本信息

**Path：** /v1/trade/web/orders/oneClickCancel

**Method：** POST

**接口描述：**
<p></p>

### 请求参数
**Headers**

| 参数名称  | 参数值  |  是否必须 | 示例  | 备注  |
| ------------ | ------------ | ------------ | ------------ | ------------ |
| Content-Type  |  application/json | 是  |  application/json |   |
**Body**

<table>
  <thead class="ant-table-thead">
    <tr>
      <th key=name>名称</th><th key=type>类型</th><th key=required>是否必须</th><th key=default>默认值</th><th key=desc>备注</th><th key=sub>其他信息</th>
    </tr>
  </thead><tbody className="ant-table-tbody"><tr key=0-0><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> tradeType</span></td><td key=1><span>string</span></td><td key=2>必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">交易类型，正向合约：linearPerpetual</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>linearPerpetual</span></p></td></tr><tr key=0-1><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> symbol</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">交易对。常用形式为“基础货币”+“报价货币”</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>BTCUSDT</span></p></td></tr>
               </tbody>
              </table>
            
### 返回数据

<table>
  <thead class="ant-table-thead">
    <tr>
      <th key=name>名称</th><th key=type>类型</th><th key=required>是否必须</th><th key=default>默认值</th><th key=desc>备注</th><th key=sub>其他信息</th>
    </tr>
  </thead><tbody className="ant-table-tbody"><tr key=0-0><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> msg</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">请求结果描述。请求成功返回成功描述。发生错误返回具体错误描述。</span></td><td key=5></td></tr><tr key=0-1><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> data</span></td><td key=1><span>object</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">数据</span></td><td key=5></td></tr><tr key=0-2><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> code</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">错误码</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1</span></p></td></tr><tr key=0-3><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> ts</span></td><td key=1><span>integer</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">系统时间</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1660101471921</span></p></td></tr><tr key=0-4><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> traceId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr>
               </tbody>
              </table>
            
## 二次确认
<a id=二次确认2709> </a>
### 基本信息

**Path：** /v1/trade/web/orders/preview

**Method：** GET

**接口描述：**
<p></p>

### 请求参数
**Query**

| 参数名称  |  是否必须 | 示例  | 备注  |
| ------------ | ------------ | ------------ | ------------ |
| tradeType | 是  |   |  交易类型，正向合约：linearPerpetual |
| symbol | 是  |   |  交易对。常用形式为“基础货币”+“报价货币” |
| side | 是  |   |  交易方向，1:buy, 2:sell, buy表示买，sell表示卖。 |
| positionSide | 否  |   |  持仓方向，单向持仓模式下非必填，默认且仅可填both;在双向持仓模式下必填,且仅可选择 long 或 short---只适用于合约业务 |
| orderType | 是  |   |  订单类型。可接受的值：market、limit----只适用于合约业务 |
| reduceOnly | 否  |  false |  只减仓。是传true，否的话false，默认是false--只适用于合约业务的单向持仓 |
| marginType | 否  |   |  交易模式：保证金模式：isolated：逐仓 ；cross：全仓 非保证金模式：cash：非保证金 |
| price | 否  |   |  委托价格。如果是下限价单，该参数为必填。 |
| priceType | 否  |   |  开仓成交价格类型，仅对市价单和STOP单有效。枚举类型有：marketPrice；optimalFive ，默认为marketPrice |
| orderQty | 否  |   |  委托数量（张） |
| postOnly | 否  |  false |  可选执行说明。有效选项：postOnly。默认传false，如果为true，一定要只挂单。如果立刻成交，则撤单。--只适用于合约业务 |
| timeInForce | 否  |   |  GTC/IOC/FOK，默认是 GTC--只适用于合约业务 |
| currency | 否  |   |  币种 |

### 返回数据

<table>
  <thead class="ant-table-thead">
    <tr>
      <th key=name>名称</th><th key=type>类型</th><th key=required>是否必须</th><th key=default>默认值</th><th key=desc>备注</th><th key=sub>其他信息</th>
    </tr>
  </thead><tbody className="ant-table-tbody"><tr key=0-0><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> msg</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">请求结果描述。请求成功返回成功描述。发生错误返回具体错误描述。</span></td><td key=5></td></tr><tr key=0-1><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> data</span></td><td key=1><span>object</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">数据</span></td><td key=5></td></tr><tr key=0-1-0><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> liquidationPrice</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">预估强平价</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>19300</span></p></td></tr><tr key=0-1-1><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> liquidationPriceDiff</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">预估强平价距离标记价格差距</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1300</span></p></td></tr><tr key=0-1-2><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> liquidationPriceDiffRate</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">预估强平价距离标记价格差距百分比</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>-0.0344</span></p></td></tr><tr key=0-2><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> code</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">错误码</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1</span></p></td></tr><tr key=0-3><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> ts</span></td><td key=1><span>integer</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">系统时间</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1660101471921</span></p></td></tr><tr key=0-4><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> traceId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr>
               </tbody>
              </table>
            
## 单个下单
<a id=单个下单2709> </a>
### 基本信息

**Path：** /v1/trade/web/orders

**Method：** POST

**接口描述：**
<p></p>

### 请求参数
**Headers**

| 参数名称  | 参数值  |  是否必须 | 示例  | 备注  |
| ------------ | ------------ | ------------ | ------------ | ------------ |
| Content-Type  |  application/json | 是  |  application/json |   |
**Body**

<table>
  <thead class="ant-table-thead">
    <tr>
      <th key=name>名称</th><th key=type>类型</th><th key=required>是否必须</th><th key=default>默认值</th><th key=desc>备注</th><th key=sub>其他信息</th>
    </tr>
  </thead><tbody className="ant-table-tbody"><tr key=0-0><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> tradeType</span></td><td key=1><span>string</span></td><td key=2>必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">交易类型，正向合约：linearPerpetual</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>linearPerpetual</span></p></td></tr><tr key=0-1><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> symbol</span></td><td key=1><span>string</span></td><td key=2>必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">交易对。常用形式为“基础货币”+“报价货币”</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>BTCUSDT</span></p></td></tr><tr key=0-2><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> side</span></td><td key=1><span>string</span></td><td key=2>必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">交易方向，1:buy, 2:sell, buy表示买，sell表示卖。</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>buy</span></p></td></tr><tr key=0-3><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> positionSide</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">持仓方向，单向持仓模式下非必填，默认且仅可填both;在双向持仓模式下必填,且仅可选择 long 或 short---只适用于合约业务</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>long</span></p></td></tr><tr key=0-4><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> orderType</span></td><td key=1><span>string</span></td><td key=2>必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">订单类型。可接受的值：market、limit----只适用于合约业务</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>limit</span></p></td></tr><tr key=0-5><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> reduceOnly</span></td><td key=1><span>boolean</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">只减仓。是传true，否的话false，默认是false--只适用于合约业务的单向持仓</span></td><td key=5><p key=1><span style="font-weight: '700'">mock: </span><span>false</span></p></td></tr><tr key=0-6><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> marginType</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">交易模式：保证金模式：isolated：逐仓 ；cross：全仓 非保证金模式：cash：非保证金</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>cross</span></p></td></tr><tr key=0-7><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> price</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">委托价格。如果是下限价单，该参数为必填。</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>20000</span></p></td></tr><tr key=0-8><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> priceType</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">开仓成交价格类型，仅对市价单和STOP单有效。枚举类型有：marketPrice；optimalFive ，默认为marketPrice</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>optimalN</span></p></td></tr><tr key=0-9><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> orderQty</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">委托数量（张）</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1</span></p></td></tr><tr key=0-10><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> postOnly</span></td><td key=1><span>boolean</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">可选执行说明。有效选项：postOnly。默认传false，如果为true，一定要只挂单。如果立刻成交，则撤单。--只适用于合约业务</span></td><td key=5><p key=1><span style="font-weight: '700'">mock: </span><span>false</span></p></td></tr><tr key=0-11><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> timeInForce</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">GTC/IOC/FOK，默认是 GTC--只适用于合约业务</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>GTC</span></p></td></tr><tr key=0-12><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> currency</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">币种</span></td><td key=5></td></tr>
               </tbody>
              </table>
            
### 返回数据

<table>
  <thead class="ant-table-thead">
    <tr>
      <th key=name>名称</th><th key=type>类型</th><th key=required>是否必须</th><th key=default>默认值</th><th key=desc>备注</th><th key=sub>其他信息</th>
    </tr>
  </thead><tbody className="ant-table-tbody"><tr key=0-0><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> msg</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">请求结果描述。请求成功返回成功描述。发生错误返回具体错误描述。</span></td><td key=5></td></tr><tr key=0-1><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> data</span></td><td key=1><span>object</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">数据</span></td><td key=5></td></tr><tr key=0-1-0><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> orderId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">订单号</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>12345678901234567890</span></p></td></tr><tr key=0-1-1><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> createTime</span></td><td key=1><span>integer</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">创建时间</span></td><td key=5></td></tr><tr key=0-2><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> code</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">错误码</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1</span></p></td></tr><tr key=0-3><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> ts</span></td><td key=1><span>integer</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">系统时间</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1660101471921</span></p></td></tr><tr key=0-4><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> traceId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr>
               </tbody>
              </table>
            
## 单个下单, 提供给压测使用
<a id=单个下单, 提供给压测使用2709> </a>
### 基本信息

**Path：** /v1/trade/web/orders/test

**Method：** POST

**接口描述：**
<p></p>

### 请求参数
**Headers**

| 参数名称  | 参数值  |  是否必须 | 示例  | 备注  |
| ------------ | ------------ | ------------ | ------------ | ------------ |
| Content-Type  |  application/json | 是  |  application/json |   |
**Body**

<table>
  <thead class="ant-table-thead">
    <tr>
      <th key=name>名称</th><th key=type>类型</th><th key=required>是否必须</th><th key=default>默认值</th><th key=desc>备注</th><th key=sub>其他信息</th>
    </tr>
  </thead><tbody className="ant-table-tbody"><tr key=0-0><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> tradeType</span></td><td key=1><span>string</span></td><td key=2>必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">交易类型，正向合约：linearPerpetual</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>linearPerpetual</span></p></td></tr><tr key=0-1><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> symbol</span></td><td key=1><span>string</span></td><td key=2>必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">交易对。常用形式为“基础货币”+“报价货币”</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>BTCUSDT</span></p></td></tr><tr key=0-2><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> side</span></td><td key=1><span>string</span></td><td key=2>必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">交易方向，1:buy, 2:sell, buy表示买，sell表示卖。</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>buy</span></p></td></tr><tr key=0-3><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> positionSide</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">持仓方向，单向持仓模式下非必填，默认且仅可填both;在双向持仓模式下必填,且仅可选择 long 或 short---只适用于合约业务</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>long</span></p></td></tr><tr key=0-4><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> orderType</span></td><td key=1><span>string</span></td><td key=2>必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">订单类型。可接受的值：market、limit----只适用于合约业务</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>limit</span></p></td></tr><tr key=0-5><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> reduceOnly</span></td><td key=1><span>boolean</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">只减仓。是传true，否的话false，默认是false--只适用于合约业务的单向持仓</span></td><td key=5><p key=1><span style="font-weight: '700'">mock: </span><span>false</span></p></td></tr><tr key=0-6><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> marginType</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">交易模式：保证金模式：isolated：逐仓 ；cross：全仓 非保证金模式：cash：非保证金</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>cross</span></p></td></tr><tr key=0-7><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> price</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">委托价格。如果是下限价单，该参数为必填。</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>20000</span></p></td></tr><tr key=0-8><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> priceType</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">开仓成交价格类型，仅对市价单和STOP单有效。枚举类型有：marketPrice；optimalFive ，默认为marketPrice</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>optimalN</span></p></td></tr><tr key=0-9><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> orderQty</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">委托数量（张）</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1</span></p></td></tr><tr key=0-10><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> clOrdId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">用户自定义订单ID</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>123456</span></p></td></tr><tr key=0-11><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> postOnly</span></td><td key=1><span>boolean</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">可选执行说明。有效选项：postOnly。默认传false，如果为true，一定要只挂单。如果立刻成交，则撤单。--只适用于合约业务</span></td><td key=5><p key=1><span style="font-weight: '700'">mock: </span><span>false</span></p></td></tr><tr key=0-12><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> timeInForce</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">GTC/IOC/FOK，默认是 GTC--只适用于合约业务</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>GTC</span></p></td></tr><tr key=0-13><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> currency</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">币种</span></td><td key=5></td></tr><tr key=0-14><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> startTime</span></td><td key=1><span>integer</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">透传时间</span></td><td key=5></td></tr>
               </tbody>
              </table>
            
### 返回数据

<table>
  <thead class="ant-table-thead">
    <tr>
      <th key=name>名称</th><th key=type>类型</th><th key=required>是否必须</th><th key=default>默认值</th><th key=desc>备注</th><th key=sub>其他信息</th>
    </tr>
  </thead><tbody className="ant-table-tbody"><tr key=0-0><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> msg</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">请求结果描述。请求成功返回成功描述。发生错误返回具体错误描述。</span></td><td key=5></td></tr><tr key=0-1><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> data</span></td><td key=1><span>object</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">数据</span></td><td key=5></td></tr><tr key=0-1-0><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> orderId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">订单号</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>12345678901234567890</span></p></td></tr><tr key=0-1-1><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> clOrdId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">客户端ID</span></td><td key=5></td></tr><tr key=0-1-2><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> createTime</span></td><td key=1><span>integer</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">创建时间</span></td><td key=5></td></tr><tr key=0-2><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> code</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">错误码</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1</span></p></td></tr><tr key=0-3><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> ts</span></td><td key=1><span>integer</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">系统时间</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1660101471921</span></p></td></tr><tr key=0-4><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> traceId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr>
               </tbody>
              </table>
            
## 单个撤单
<a id=单个撤单2709> </a>
### 基本信息

**Path：** /v1/trade/web/orders/cancel

**Method：** POST

**接口描述：**
<p></p>

### 请求参数
**Headers**

| 参数名称  | 参数值  |  是否必须 | 示例  | 备注  |
| ------------ | ------------ | ------------ | ------------ | ------------ |
| Content-Type  |  application/json | 是  |  application/json |   |
**Body**

<table>
  <thead class="ant-table-thead">
    <tr>
      <th key=name>名称</th><th key=type>类型</th><th key=required>是否必须</th><th key=default>默认值</th><th key=desc>备注</th><th key=sub>其他信息</th>
    </tr>
  </thead><tbody className="ant-table-tbody"><tr key=0-0><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> tradeType</span></td><td key=1><span>string</span></td><td key=2>必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">交易类型，正向合约：linearPerpetual</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>linearPerpetual</span></p></td></tr><tr key=0-1><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> symbol</span></td><td key=1><span>string</span></td><td key=2>必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">交易对。常用形式为“基础货币”+“报价货币”</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>BTCUSDT</span></p></td></tr><tr key=0-2><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> orderId</span></td><td key=1><span>string</span></td><td key=2>必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">要撤消的订单的订单 ID</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>123456023424242423</span></p></td></tr><tr key=0-3><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> currency</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">币种</span></td><td key=5></td></tr>
               </tbody>
              </table>
            
### 返回数据

<table>
  <thead class="ant-table-thead">
    <tr>
      <th key=name>名称</th><th key=type>类型</th><th key=required>是否必须</th><th key=default>默认值</th><th key=desc>备注</th><th key=sub>其他信息</th>
    </tr>
  </thead><tbody className="ant-table-tbody"><tr key=0-0><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> msg</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">请求结果描述。请求成功返回成功描述。发生错误返回具体错误描述。</span></td><td key=5></td></tr><tr key=0-1><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> data</span></td><td key=1><span>object</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">数据</span></td><td key=5></td></tr><tr key=0-1-0><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> orderId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">要撤消的订单的订单 ID</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1234562342424234</span></p></td></tr><tr key=0-2><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> code</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">错误码</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1</span></p></td></tr><tr key=0-3><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> ts</span></td><td key=1><span>integer</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">系统时间</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1660101471921</span></p></td></tr><tr key=0-4><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> traceId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr>
               </tbody>
              </table>
            
## 单个撤单, 提供给压测使用
<a id=单个撤单, 提供给压测使用2709> </a>
### 基本信息

**Path：** /v1/trade/web/orders/cancel/test

**Method：** POST

**接口描述：**
<p></p>

### 请求参数
**Headers**

| 参数名称  | 参数值  |  是否必须 | 示例  | 备注  |
| ------------ | ------------ | ------------ | ------------ | ------------ |
| Content-Type  |  application/json | 是  |  application/json |   |
**Body**

<table>
  <thead class="ant-table-thead">
    <tr>
      <th key=name>名称</th><th key=type>类型</th><th key=required>是否必须</th><th key=default>默认值</th><th key=desc>备注</th><th key=sub>其他信息</th>
    </tr>
  </thead><tbody className="ant-table-tbody"><tr key=0-0><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> tradeType</span></td><td key=1><span>string</span></td><td key=2>必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">交易类型，正向永续：linearSwap，币本位:swap--先定义永续</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>linearSwap</span></p></td></tr><tr key=0-1><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> symbol</span></td><td key=1><span>string</span></td><td key=2>必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">交易对。常用形式为“基础货币”+“报价货币”</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>BTCUSDT</span></p></td></tr><tr key=0-2><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> orderId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">要撤消的订单的订单 ID</span></td><td key=5></td></tr><tr key=0-3><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> clOrdId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">用户自定义订单ID</span></td><td key=5></td></tr><tr key=0-4><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> currency</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">币种</span></td><td key=5></td></tr><tr key=0-5><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> startTime</span></td><td key=1><span>integer</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">透传时间</span></td><td key=5></td></tr>
               </tbody>
              </table>
            
### 返回数据

<table>
  <thead class="ant-table-thead">
    <tr>
      <th key=name>名称</th><th key=type>类型</th><th key=required>是否必须</th><th key=default>默认值</th><th key=desc>备注</th><th key=sub>其他信息</th>
    </tr>
  </thead><tbody className="ant-table-tbody"><tr key=0-0><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> msg</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">请求结果描述。请求成功返回成功描述。发生错误返回具体错误描述。</span></td><td key=5></td></tr><tr key=0-1><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> data</span></td><td key=1><span>object</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">数据</span></td><td key=5></td></tr><tr key=0-1-0><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> orderId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">要撤消的订单的订单 ID</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1000342432424234</span></p></td></tr><tr key=0-1-1><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> clOrdId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">用户自定义订单ID</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>123235345</span></p></td></tr><tr key=0-1-2><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> code</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">code</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1001</span></p></td></tr><tr key=0-2><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> code</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">错误码</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1</span></p></td></tr><tr key=0-3><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> ts</span></td><td key=1><span>integer</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">系统时间</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1660101471921</span></p></td></tr><tr key=0-4><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> traceId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr>
               </tbody>
              </table>
            
## 查看当前委托
<a id=查看当前委托2709> </a>
### 基本信息

**Path：** /v1/trade/web/openOrders

**Method：** GET

**接口描述：**
<p></p>

### 请求参数
**Query**

| 参数名称  |  是否必须 | 示例  | 备注  |
| ------------ | ------------ | ------------ | ------------ |
| tradeType | 是  |   |  交易类型 |
| side | 否  |   |  交易方向。buy：买 sell：卖 |
| symbol | 否  |   |  交易对 |
| orderId | 否  |   |  AAX 订单编号 |
| clOrdId | 否  |   |  客户订单号 |
| pageNum | 否  |   |  分页页码 |
| pageSize | 否  |   |  分页条数 |

### 返回数据

<table>
  <thead class="ant-table-thead">
    <tr>
      <th key=name>名称</th><th key=type>类型</th><th key=required>是否必须</th><th key=default>默认值</th><th key=desc>备注</th><th key=sub>其他信息</th>
    </tr>
  </thead><tbody className="ant-table-tbody"><tr key=0-0><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> msg</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">请求结果描述。请求成功返回成功描述。发生错误返回具体错误描述。</span></td><td key=5></td></tr><tr key=0-1><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> data</span></td><td key=1><span>object</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">数据</span></td><td key=5></td></tr><tr key=0-1-0><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> pageNum</span></td><td key=1><span>integer</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">当前页码</span></td><td key=5></td></tr><tr key=0-1-1><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> pageSize</span></td><td key=1><span>integer</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">每页显示的条数</span></td><td key=5></td></tr><tr key=0-1-2><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> totalSize</span></td><td key=1><span>integer</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">总条数</span></td><td key=5></td></tr><tr key=0-1-3><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> totalPage</span></td><td key=1><span>integer</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">总页数</span></td><td key=5></td></tr><tr key=0-1-4><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> list</span></td><td key=1><span>object []</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">分页数据</span></td><td key=5><p key=3><span style="font-weight: '700'">item 类型: </span><span>object</span></p></td></tr><tr key=0-1-4-0><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> uid</span></td><td key=1><span>integer</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">用户UID</span></td><td key=5></td></tr><tr key=0-1-4-1><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> tradeType</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">交易类型</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>linearPerpetual</span></p></td></tr><tr key=0-1-4-2><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> symbol</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">交易对</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>BTCUSDT</span></p></td></tr><tr key=0-1-4-3><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> positionSide</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">持仓方向</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>long</span></p></td></tr><tr key=0-1-4-4><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> side</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">交易方向。buy：买 sell：卖</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>buy</span></p></td></tr><tr key=0-1-4-5><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> marginType</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">保证金模式。isolated：逐仓 ；cross：全仓</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>isolated</span></p></td></tr><tr key=0-1-4-6><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> clOrdId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">用户自定义订单ID</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>116793457822</span></p></td></tr><tr key=0-1-4-7><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> createTime</span></td><td key=1><span>integer</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">订单创建时间</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>114599907</span></p></td></tr><tr key=0-1-4-8><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> orderQty</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">委托数量</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>100</span></p></td></tr><tr key=0-1-4-9><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> cumQty</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">订单的累计成交张数</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>100</span></p></td></tr><tr key=0-1-4-10><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> avgPrice</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">成交均价-币安、OK、火币</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>20014.43</span></p></td></tr><tr key=0-1-4-11><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> lastPrice</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">最后一笔成交价格-币安、OK、火币</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>21005.32</span></p></td></tr><tr key=0-1-4-12><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> leavesQty</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">还未成交的订单张数</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>78</span></p></td></tr><tr key=0-1-4-13><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> leverage</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">杠杆</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>5</span></p></td></tr><tr key=0-1-4-14><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> commission</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">已成交手续费-OK、火币</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>0.41</span></p></td></tr><tr key=0-1-4-15><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> commissionAsset</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">手续费币种-OK、火币</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>usdt</span></p></td></tr><tr key=0-1-4-16><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> orderId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">AAX 订单编号</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>578982224773</span></p></td></tr><tr key=0-1-4-17><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> orderType</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">订单类型。可接受的值：market、limit----只适用于合约业务。若是market，则默认timeInForce是IOC</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>market</span></p></td></tr><tr key=0-1-4-18><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> priceType</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">开仓成交价格类型，仅对市价单和STOP单有效。枚举类型有：marketPrice；optimalFive ，默认为marketPrice</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>optimalN</span></p></td></tr><tr key=0-1-4-19><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> price</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">委托价格</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>21000</span></p></td></tr><tr key=0-1-4-20><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> reduceOnly</span></td><td key=1><span>boolean</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">只减仓。是传true，否的话false，默认是false--只适用于合约业务的单向持仓</span></td><td key=5><p key=1><span style="font-weight: '700'">mock: </span><span>false</span></p></td></tr><tr key=0-1-4-21><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> updateTime</span></td><td key=1><span>integer</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">订单的最后更新时间</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>6752515411</span></p></td></tr><tr key=0-1-4-22><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> postOnly</span></td><td key=1><span>boolean</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">默认传false，如果为true，一定要只挂单。如果立刻成交，则撤单。--只适用于合约业务</span></td><td key=5><p key=1><span style="font-weight: '700'">mock: </span><span>false</span></p></td></tr><tr key=0-1-4-23><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> orderStatus</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">订单状态</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>0</span></p></td></tr><tr key=0-1-4-24><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> timeInForce</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">GTC/IOC/FOK，默认是 GTC。请留意，IOC/FOK单的费率是普通订单费率的1.5倍。--只适用于合约业务</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>GTC</span></p></td></tr><tr key=0-1-4-25><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> base</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">标的资产</span></td><td key=5></td></tr><tr key=0-1-4-26><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> quote</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">结算资产</span></td><td key=5></td></tr><tr key=0-1-4-27><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> openFrozenMargin</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">冻结保证金</span></td><td key=5></td></tr><tr key=0-2><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> code</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">错误码</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1</span></p></td></tr><tr key=0-3><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> ts</span></td><td key=1><span>integer</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">系统时间</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1660101471921</span></p></td></tr><tr key=0-4><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> traceId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr>
               </tbody>
              </table>
            
## 查看用户全部币对
<a id=查看用户全部币对2709> </a>
### 基本信息

**Path：** /v1/trade/web/user/allSymbol

**Method：** GET

**接口描述：**
<p></p>

### 请求参数
**Query**

| 参数名称  |  是否必须 | 示例  | 备注  |
| ------------ | ------------ | ------------ | ------------ |
| type | 是  |   |  查询委托类型. currentOrder 当前委托, conditionOrder 条件委托 |

### 返回数据

<table>
  <thead class="ant-table-thead">
    <tr>
      <th key=name>名称</th><th key=type>类型</th><th key=required>是否必须</th><th key=default>默认值</th><th key=desc>备注</th><th key=sub>其他信息</th>
    </tr>
  </thead><tbody className="ant-table-tbody"><tr key=0-0><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> msg</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">请求结果描述。请求成功返回成功描述。发生错误返回具体错误描述。</span></td><td key=5></td></tr><tr key=0-1><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> data</span></td><td key=1><span>string []</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">数据</span></td><td key=5><p key=3><span style="font-weight: '700'">item 类型: </span><span>string</span></p></td></tr><tr key=array-2><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> </span></td><td key=1><span></span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr><tr key=0-2><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> code</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">错误码</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1</span></p></td></tr><tr key=0-3><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> ts</span></td><td key=1><span>integer</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">系统时间</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1660101471921</span></p></td></tr><tr key=0-4><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> traceId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr>
               </tbody>
              </table>
            
# webApi 持仓

## 持仓查询接口
<a id=持仓查询接口2714> </a>
### 基本信息

**Path：** /v1/trade/web/position

**Method：** GET

**接口描述：**
<p></p>

### 请求参数
**Query**

| 参数名称  |  是否必须 | 示例  | 备注  |
| ------------ | ------------ | ------------ | ------------ |
| tradeType | 是  |   |  业务线 |
| symbol | 否  |   |  交易对 |
| marginType | 否  |   |  交易模式：保证金模式：isolated：逐仓 ；cross：全仓 |

### 返回数据

<table>
  <thead class="ant-table-thead">
    <tr>
      <th key=name>名称</th><th key=type>类型</th><th key=required>是否必须</th><th key=default>默认值</th><th key=desc>备注</th><th key=sub>其他信息</th>
    </tr>
  </thead><tbody className="ant-table-tbody"><tr key=0-0><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> msg</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">请求结果描述。请求成功返回成功描述。发生错误返回具体错误描述。</span></td><td key=5></td></tr><tr key=0-1><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> data</span></td><td key=1><span>object []</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">数据</span></td><td key=5><p key=3><span style="font-weight: '700'">item 类型: </span><span>object</span></p></td></tr><tr key=0-1-0><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> tradeType</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">交易类型</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>linearPerpetual</span></p></td></tr><tr key=0-1-1><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> side</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">买卖方向</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>buy</span></p></td></tr><tr key=0-1-2><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> positionSide</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">持仓方向</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>long</span></p></td></tr><tr key=0-1-3><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> symbol</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">交易对</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>BTCUSDT</span></p></td></tr><tr key=0-1-4><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> marginType</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">仓位类型。isolated：逐仓 ；cross：全仓</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>isolated</span></p></td></tr><tr key=0-1-5><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> avgEntryPrice</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">开仓均价</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>21004.43</span></p></td></tr><tr key=0-1-6><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> positionAmt</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">持仓数量（张）</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>100</span></p></td></tr><tr key=0-1-7><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> posMargin</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">持仓保证金</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>30100.31</span></p></td></tr><tr key=0-1-8><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> leverage</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">杠杆</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>2</span></p></td></tr><tr key=0-1-9><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> liquidationPrice</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">预估强平价格</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>20010.3</span></p></td></tr><tr key=0-1-10><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> unrealisedPnl</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">未实现盈亏</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1.3</span></p></td></tr><tr key=0-1-11><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> earningRate</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">收益率</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>3.4</span></p></td></tr><tr key=0-1-12><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> markPrice</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">标记价格</span></td><td key=5></td></tr><tr key=0-1-13><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> base</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">标的资产</span></td><td key=5></td></tr><tr key=0-1-14><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> quote</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">结算资产</span></td><td key=5></td></tr><tr key=0-1-15><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> positionId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">持仓ID</span></td><td key=5></td></tr><tr key=0-1-16><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> availPos</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">仓位可平数量</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>10</span></p></td></tr><tr key=0-1-17><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> fixedAvailableWithdraw</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">逐仓最大可转</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>10</span></p></td></tr><tr key=0-1-18><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> isLiquidate</span></td><td key=1><span>boolean</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">是否爆仓中</span></td><td key=5><p key=1><span style="font-weight: '700'">mock: </span><span>false</span></p></td></tr><tr key=0-1-19><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> marginRate</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">保证金比率</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1.8</span></p></td></tr><tr key=0-1-20><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> openTime</span></td><td key=1><span>integer</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">开仓时间</span></td><td key=5></td></tr><tr key=0-1-21><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> indexPrice</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">指数价格</span></td><td key=5></td></tr><tr key=0-1-22><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> tradePrice</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">最新成交价价格</span></td><td key=5></td></tr><tr key=0-1-23><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> balance</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">逐仓余额</span></td><td key=5></td></tr><tr key=0-1-24><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> fundingRate</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">资金费率</span></td><td key=5></td></tr><tr key=0-2><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> code</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">错误码</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1</span></p></td></tr><tr key=0-3><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> ts</span></td><td key=1><span>integer</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">系统时间</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1660101471921</span></p></td></tr><tr key=0-4><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> traceId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr>
               </tbody>
              </table>
            
## 调整逐仓保证金
<a id=调整逐仓保证金2714> </a>
### 基本信息

**Path：** /v1/trade/web/position/margin

**Method：** POST

**接口描述：**
<p></p>

### 请求参数
**Headers**

| 参数名称  | 参数值  |  是否必须 | 示例  | 备注  |
| ------------ | ------------ | ------------ | ------------ | ------------ |
| Content-Type  |  application/json | 是  |  application/json |   |
**Body**

<table>
  <thead class="ant-table-thead">
    <tr>
      <th key=name>名称</th><th key=type>类型</th><th key=required>是否必须</th><th key=default>默认值</th><th key=desc>备注</th><th key=sub>其他信息</th>
    </tr>
  </thead><tbody className="ant-table-tbody"><tr key=0-0><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> tradeType</span></td><td key=1><span>string</span></td><td key=2>必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">交易类型，正向永续：linearPerpetual，币本位:inversePerpetual</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>linearPerpetual</span></p></td></tr><tr key=0-1><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> symbol</span></td><td key=1><span>string</span></td><td key=2>必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">交易对</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>BTCUSDT</span></p></td></tr><tr key=0-2><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> positionSide</span></td><td key=1><span>string</span></td><td key=2>必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">持仓方向，单向持仓模式下默认返回both;在双向持仓模式下 long 或 short</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>long</span></p></td></tr><tr key=0-3><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> amount</span></td><td key=1><span>string</span></td><td key=2>必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">调整金额</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1.5</span></p></td></tr><tr key=0-4><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> type</span></td><td key=1><span>integer</span></td><td key=2>必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">调整方向 1: 增加逐仓保证金，2: 减少逐仓保证金</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1</span></p></td></tr>
               </tbody>
              </table>
            
### 返回数据

<table>
  <thead class="ant-table-thead">
    <tr>
      <th key=name>名称</th><th key=type>类型</th><th key=required>是否必须</th><th key=default>默认值</th><th key=desc>备注</th><th key=sub>其他信息</th>
    </tr>
  </thead><tbody className="ant-table-tbody"><tr key=0-0><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> msg</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">请求结果描述。请求成功返回成功描述。发生错误返回具体错误描述。</span></td><td key=5></td></tr><tr key=0-1><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> data</span></td><td key=1><span>object</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">数据</span></td><td key=5></td></tr><tr key=0-1-0><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> tradeType</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">交易类型，正向永续：linearPerpetual，币本位:inversePerpetual</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>linearPerpetual</span></p></td></tr><tr key=0-1-1><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> symbol</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">交易对</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>BTCUSDT</span></p></td></tr><tr key=0-1-2><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> amount</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">调整金额</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1.5</span></p></td></tr><tr key=0-1-3><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> type</span></td><td key=1><span>integer</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">调整方向 1: 增加逐仓保证金，2: 减少逐仓保证金</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1</span></p></td></tr><tr key=0-1-4><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> currency</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">保证金增加的币种，例如USDT</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>USDT</span></p></td></tr><tr key=0-2><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> code</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">错误码</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1</span></p></td></tr><tr key=0-3><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> ts</span></td><td key=1><span>integer</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">系统时间</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1660101471921</span></p></td></tr><tr key=0-4><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> traceId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr>
               </tbody>
              </table>
            
# webApi 查看风险限额

## 查看用户全部风险限额
<a id=查看用户全部风险限额2719> </a>
### 基本信息

**Path：** /v1/trade/web/allRiskLimit

**Method：** GET

**接口描述：**
<p></p>

### 请求参数
**Query**

| 参数名称  |  是否必须 | 示例  | 备注  |
| ------------ | ------------ | ------------ | ------------ |
| tradeType | 是  |   |  交易类型，正向永续：linearPerpetual，币本位:inversePerpetual |
| symbol | 是  |   |  交易对 |
| marginType | 否  |   |  交易模式：保证金模式：isolated：逐仓 ；cross：全仓 |

### 返回数据

<table>
  <thead class="ant-table-thead">
    <tr>
      <th key=name>名称</th><th key=type>类型</th><th key=required>是否必须</th><th key=default>默认值</th><th key=desc>备注</th><th key=sub>其他信息</th>
    </tr>
  </thead><tbody className="ant-table-tbody"><tr key=0-0><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> msg</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">请求结果描述。请求成功返回成功描述。发生错误返回具体错误描述。</span></td><td key=5></td></tr><tr key=0-1><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> data</span></td><td key=1><span>object []</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">数据</span></td><td key=5><p key=3><span style="font-weight: '700'">item 类型: </span><span>object</span></p></td></tr><tr key=0-1-0><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> tradeType</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">交易类型</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>linearPerpetual</span></p></td></tr><tr key=0-1-1><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> symbol</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">交易对</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>BTCUSDT</span></p></td></tr><tr key=0-1-2><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> marginType</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">保证金模式</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>cross</span></p></td></tr><tr key=0-1-3><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> bracket</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">层级，属于第几层的风险限额</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1</span></p></td></tr><tr key=0-1-4><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> initialLeverage</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">该层允许的最高初始杠杆倍数</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>10</span></p></td></tr><tr key=0-1-5><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> notionalCap</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">该层对应的价值上限</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>10</span></p></td></tr><tr key=0-1-6><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> notionalFloor</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">该层对应的价值下限</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>10</span></p></td></tr><tr key=0-1-7><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> marginRate</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">该层对应的初始保证金率</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>10</span></p></td></tr><tr key=0-1-8><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> maintMarginRatio</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">该层对应的维持保证金率</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>10</span></p></td></tr><tr key=0-2><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> code</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">错误码</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1</span></p></td></tr><tr key=0-3><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> ts</span></td><td key=1><span>integer</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">系统时间</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1660101471921</span></p></td></tr><tr key=0-4><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> traceId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr>
               </tbody>
              </table>
            
## 查看用户风险限额列表
<a id=查看用户风险限额列表2719> </a>
### 基本信息

**Path：** /v1/trade/web/list/riskLimit

**Method：** GET

**接口描述：**
<p></p>

### 请求参数
**Query**

| 参数名称  |  是否必须 | 示例  | 备注  |
| ------------ | ------------ | ------------ | ------------ |
| tradeType | 是  |   |  交易类型，正向永续：linearPerpetual，币本位:inversePerpetual |
| symbol | 是  |   |  交易对 |
| marginType | 否  |   |  交易模式：保证金模式：isolated：逐仓 ；cross：全仓 |

### 返回数据

<table>
  <thead class="ant-table-thead">
    <tr>
      <th key=name>名称</th><th key=type>类型</th><th key=required>是否必须</th><th key=default>默认值</th><th key=desc>备注</th><th key=sub>其他信息</th>
    </tr>
  </thead><tbody className="ant-table-tbody"><tr key=0-0><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> msg</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">请求结果描述。请求成功返回成功描述。发生错误返回具体错误描述。</span></td><td key=5></td></tr><tr key=0-1><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> data</span></td><td key=1><span>object</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">数据</span></td><td key=5></td></tr><tr key=0-1-0><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> maintenanceMarginRate</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">维持保证金率(第1档)</span></td><td key=5></td></tr><tr key=0-1-1><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> maxLeverage</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">最大杠杆(第1档)</span></td><td key=5></td></tr><tr key=0-1-2><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> ctVal</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">合约面值</span></td><td key=5></td></tr><tr key=0-1-3><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> riskLimits</span></td><td key=1><span>object []</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5><p key=3><span style="font-weight: '700'">item 类型: </span><span>object</span></p></td></tr><tr key=0-1-3-0><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> uid</span></td><td key=1><span>integer</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">用户ID</span></td><td key=5></td></tr><tr key=0-1-3-1><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> vip</span></td><td key=1><span>integer</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">会员等级</span></td><td key=5></td></tr><tr key=0-1-3-2><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> tradeType</span></td><td key=1><span>integer</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">业务类型</span></td><td key=5></td></tr><tr key=0-1-3-3><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> symbol</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">交易对</span></td><td key=5></td></tr><tr key=0-1-3-4><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> marginType</span></td><td key=1><span>integer</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">保证金模式：1逐仓, 2全仓</span></td><td key=5><p key=3><span style="font-weight: '700'">枚举: </span><span>0,1,2,3</span></p><p key=4><span style="font-weight: '700'">枚举备注: </span><span>0 :ALL
1 :FIXED
2 :CROSS
3 :CASH</span></p><p key=5><span style="font-weight: '700'">mock: </span><span>@pick([0,1,2,3])</span></p></td></tr><tr key=0-1-3-5><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> grade</span></td><td key=1><span>number</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">档位等级</span></td><td key=5></td></tr><tr key=0-1-3-6><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> valueLimit</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">价值限制</span></td><td key=5></td></tr><tr key=0-1-3-7><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> maintenanceMarginRate</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">维持保证金率</span></td><td key=5></td></tr><tr key=0-1-3-8><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> minMarginRate</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">最小保证金率</span></td><td key=5></td></tr><tr key=0-1-3-9><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> maxLeverage</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">最大杠杆</span></td><td key=5></td></tr><tr key=0-2><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> code</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">错误码</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1</span></p></td></tr><tr key=0-3><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> ts</span></td><td key=1><span>integer</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">系统时间</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1660101471921</span></p></td></tr><tr key=0-4><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> traceId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr>
               </tbody>
              </table>
            
## 查看风险限额-与仓位挂单对应档位
<a id=查看风险限额-与仓位挂单对应档位2719> </a>
### 基本信息

**Path：** /v1/trade/web/riskLimit

**Method：** GET

**接口描述：**
<p></p>

### 请求参数
**Query**

| 参数名称  |  是否必须 | 示例  | 备注  |
| ------------ | ------------ | ------------ | ------------ |
| tradeType | 是  |   |  交易类型，正向永续：linearPerpetual，币本位:inversePerpetual |
| symbol | 是  |   |  交易对 |
| marginType | 否  |   |  交易模式：保证金模式：isolated：逐仓 ；cross：全仓 |

### 返回数据

<table>
  <thead class="ant-table-thead">
    <tr>
      <th key=name>名称</th><th key=type>类型</th><th key=required>是否必须</th><th key=default>默认值</th><th key=desc>备注</th><th key=sub>其他信息</th>
    </tr>
  </thead><tbody className="ant-table-tbody"><tr key=0-0><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> msg</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">请求结果描述。请求成功返回成功描述。发生错误返回具体错误描述。</span></td><td key=5></td></tr><tr key=0-1><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> data</span></td><td key=1><span>object</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">数据</span></td><td key=5></td></tr><tr key=0-1-0><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> tradeType</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">交易类型</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>linearPerpetual</span></p></td></tr><tr key=0-1-1><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> symbol</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">交易对</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>BTCUSDT</span></p></td></tr><tr key=0-1-2><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> marginType</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">保证金模式</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>cross</span></p></td></tr><tr key=0-1-3><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> bracket</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">层级，属于第几层的风险限额</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1</span></p></td></tr><tr key=0-1-4><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> initialLeverage</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">该层允许的最高初始杠杆倍数</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>10</span></p></td></tr><tr key=0-1-5><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> notionalCap</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">该层对应的价值上限</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>10</span></p></td></tr><tr key=0-1-6><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> notionalFloor</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">该层对应的价值下限</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>10</span></p></td></tr><tr key=0-1-7><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> marginRate</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">该层对应的初始保证金率</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>10</span></p></td></tr><tr key=0-1-8><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> maintMarginRatio</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">该层对应的维持保证金率</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>10</span></p></td></tr><tr key=0-2><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> code</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">错误码</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1</span></p></td></tr><tr key=0-3><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> ts</span></td><td key=1><span>integer</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">系统时间</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1660101471921</span></p></td></tr><tr key=0-4><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> traceId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr>
               </tbody>
              </table>
            
# webapi 划转

## web发起划转
<a id=web发起划转2724> </a>
### 基本信息

**Path：** /v1/trade/web/account/transfer

**Method：** POST

**接口描述：**
<p></p>

### 请求参数
**Headers**

| 参数名称  | 参数值  |  是否必须 | 示例  | 备注  |
| ------------ | ------------ | ------------ | ------------ | ------------ |
| Content-Type  |  application/json | 是  |  application/json |   |
**Body**

<table>
  <thead class="ant-table-thead">
    <tr>
      <th key=name>名称</th><th key=type>类型</th><th key=required>是否必须</th><th key=default>默认值</th><th key=desc>备注</th><th key=sub>其他信息</th>
    </tr>
  </thead><tbody className="ant-table-tbody"><tr key=0-0><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> fromAccountType</span></td><td key=1><span>string</span></td><td key=2>必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">划出账户类型(合约:futures, 资金:funding, 杠杆:margin)</span></td><td key=5><p key=2><span style="font-weight: '700'">枚举: </span><span>FUTURES,FUNDING,MARGIN,PERPETUAL,EXCHANGE,OTC,WALLET</span></p><p key=3><span style="font-weight: '700'">枚举备注: </span><span>FUTURES :合约账户
「已废弃」
FUNDING :资金账户
「已废弃」
MARGIN :杠杆账户
「已废弃」
PERPETUAL :合约账户
EXCHANGE :现货账户
OTC :OTC账户
WALLET :钱包账户</span></p><p key=5><span style="font-weight: '700'">mock: </span><span>@pick(["FUTURES","FUNDING","MARGIN","PERPETUAL","EXCHANGE","OTC","WALLET"])</span></p></td></tr><tr key=0-1><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> toAccountType</span></td><td key=1><span>string</span></td><td key=2>必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">划入账户类型(合约:futures, 资金:funding, 杠杆:margin)</span></td><td key=5><p key=2><span style="font-weight: '700'">枚举: </span><span>FUTURES,FUNDING,MARGIN,PERPETUAL,EXCHANGE,OTC,WALLET</span></p><p key=3><span style="font-weight: '700'">枚举备注: </span><span>FUTURES :合约账户
「已废弃」
FUNDING :资金账户
「已废弃」
MARGIN :杠杆账户
「已废弃」
PERPETUAL :合约账户
EXCHANGE :现货账户
OTC :OTC账户
WALLET :钱包账户</span></p><p key=5><span style="font-weight: '700'">mock: </span><span>@pick(["FUTURES","FUNDING","MARGIN","PERPETUAL","EXCHANGE","OTC","WALLET"])</span></p></td></tr><tr key=0-2><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> currency</span></td><td key=1><span>string</span></td><td key=2>必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">币种</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>USDT</span></p></td></tr><tr key=0-3><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> amount</span></td><td key=1><span>string</span></td><td key=2>必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">数量</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>2.666666</span></p></td></tr>
               </tbody>
              </table>
            
### 返回数据

<table>
  <thead class="ant-table-thead">
    <tr>
      <th key=name>名称</th><th key=type>类型</th><th key=required>是否必须</th><th key=default>默认值</th><th key=desc>备注</th><th key=sub>其他信息</th>
    </tr>
  </thead><tbody className="ant-table-tbody"><tr key=0-0><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> msg</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">请求结果描述。请求成功返回成功描述。发生错误返回具体错误描述。</span></td><td key=5></td></tr><tr key=0-1><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> data</span></td><td key=1><span>object</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">数据</span></td><td key=5></td></tr><tr key=0-1-0><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> transId</span></td><td key=1><span>integer</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">划转id</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1022098876808683520</span></p></td></tr><tr key=0-1-1><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> fromAccountType</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">划出账户类型(合约:futures, 资金:funding, 杠杆:margin)</span></td><td key=5><p key=2><span style="font-weight: '700'">枚举: </span><span>FUTURES,FUNDING,MARGIN,PERPETUAL,EXCHANGE,OTC,WALLET</span></p><p key=3><span style="font-weight: '700'">枚举备注: </span><span>FUTURES :合约账户
「已废弃」
FUNDING :资金账户
「已废弃」
MARGIN :杠杆账户
「已废弃」
PERPETUAL :合约账户
EXCHANGE :现货账户
OTC :OTC账户
WALLET :钱包账户</span></p><p key=5><span style="font-weight: '700'">mock: </span><span>@pick(["FUTURES","FUNDING","MARGIN","PERPETUAL","EXCHANGE","OTC","WALLET"])</span></p></td></tr><tr key=0-1-2><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> toAccountType</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">划入账户类型(合约:futures, 资金:funding, 杠杆:margin)</span></td><td key=5><p key=2><span style="font-weight: '700'">枚举: </span><span>FUTURES,FUNDING,MARGIN,PERPETUAL,EXCHANGE,OTC,WALLET</span></p><p key=3><span style="font-weight: '700'">枚举备注: </span><span>FUTURES :合约账户
「已废弃」
FUNDING :资金账户
「已废弃」
MARGIN :杠杆账户
「已废弃」
PERPETUAL :合约账户
EXCHANGE :现货账户
OTC :OTC账户
WALLET :钱包账户</span></p><p key=5><span style="font-weight: '700'">mock: </span><span>@pick(["FUTURES","FUNDING","MARGIN","PERPETUAL","EXCHANGE","OTC","WALLET"])</span></p></td></tr><tr key=0-1-3><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> currency</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">币种</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>USDT</span></p></td></tr><tr key=0-1-4><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> amount</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">数量</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>2.666666</span></p></td></tr><tr key=0-2><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> code</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">错误码</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1</span></p></td></tr><tr key=0-3><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> ts</span></td><td key=1><span>integer</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">系统时间</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1660101471921</span></p></td></tr><tr key=0-4><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> traceId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr>
               </tbody>
              </table>
            
# webapi 计划委托

## 查询未触发计划委托
<a id=查询未触发计划委托2729> </a>
### 基本信息

**Path：** /v1/trade/web/stopOrders/search

**Method：** GET

**接口描述：**
<p></p>

### 请求参数
**Query**

| 参数名称  |  是否必须 | 示例  | 备注  |
| ------------ | ------------ | ------------ | ------------ |
| tradeType | 是  |   |  交易类型，正向永续：linearPerpetual，币本位:inversePerpetual--先定义永续 |
| symbol | 否  |   |  交易对。常用形式为“基础货币”+“报价货币” |
| marginType | 否  |   |  交易模式：保证金模式：isolated：逐仓 ；cross：全仓 非保证金模式：cash：非保证金 |
| orderType | 否  |   |  委托类型。可接受的值： triggerMarket（市价计划单）、triggerLimit（限价计划单）tpsl(止盈止损)----只适用于合约业务 |
| stopOrderId | 否  |   |  计划订单的 ID |
| positionSide | 否  |   |  持仓方向 |
| side | 否  |   |  买卖方向 |
| pageNum | 否  |   |  分页页码,默认为1 |
| pageSize | 否  |   |  分页页面大小，默认为10，最大为100。 |

### 返回数据

<table>
  <thead class="ant-table-thead">
    <tr>
      <th key=name>名称</th><th key=type>类型</th><th key=required>是否必须</th><th key=default>默认值</th><th key=desc>备注</th><th key=sub>其他信息</th>
    </tr>
  </thead><tbody className="ant-table-tbody"><tr key=0-0><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> msg</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">请求结果描述。请求成功返回成功描述。发生错误返回具体错误描述。</span></td><td key=5></td></tr><tr key=0-1><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> data</span></td><td key=1><span>object</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">数据</span></td><td key=5></td></tr><tr key=0-1-0><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> pageNum</span></td><td key=1><span>integer</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">当前页码</span></td><td key=5></td></tr><tr key=0-1-1><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> pageSize</span></td><td key=1><span>integer</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">每页显示的条数</span></td><td key=5></td></tr><tr key=0-1-2><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> totalSize</span></td><td key=1><span>integer</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">总条数</span></td><td key=5></td></tr><tr key=0-1-3><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> totalPage</span></td><td key=1><span>integer</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">总页数</span></td><td key=5></td></tr><tr key=0-1-4><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> list</span></td><td key=1><span>object []</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">分页数据</span></td><td key=5><p key=3><span style="font-weight: '700'">item 类型: </span><span>object</span></p></td></tr><tr key=0-1-4-0><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> symbol</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">交易对。常用形式为“基础货币”+“报价货币”</span></td><td key=5></td></tr><tr key=0-1-4-1><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> tradeType</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">交易类型，正向永续：linearPerpetual，币本位:inversePerpetual--先定义永续</span></td><td key=5></td></tr><tr key=0-1-4-2><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> positionSide</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">持仓方向，单向持仓模式下默认返回BOTH;在双向持仓模式下 LONG 或 SHORT---只适用于合约业务</span></td><td key=5></td></tr><tr key=0-1-4-3><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> side</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">交易方向，buy表示买，sell表示卖。</span></td><td key=5></td></tr><tr key=0-1-4-4><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> marginType</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">保证金模式：isolated：逐仓 ；cross：全仓</span></td><td key=5></td></tr><tr key=0-1-4-5><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> stopOrderId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">AAX计划委托单Id</span></td><td key=5></td></tr><tr key=0-1-4-6><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> createTime</span></td><td key=1><span>integer</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">订单创建时间</span></td><td key=5></td></tr><tr key=0-1-4-7><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> orderType</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">委托类型。可接受的值： triggerMarket（市价计划单）、triggerLimit（限价计划单）tpsl(止盈止损)----只适用于合约业务</span></td><td key=5></td></tr><tr key=0-1-4-8><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> priceType</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">成交价格类型，仅对市价单和市价计划单有效。枚举类型有：marketPrice；optimalFive ，默认为marketPrice</span></td><td key=5></td></tr><tr key=0-1-4-9><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> orderQty</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">委托数量（张）</span></td><td key=5></td></tr><tr key=0-1-4-10><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> triggerType</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">委托触发价类型 last：最新价格 index：指数价格 mark：标记价格--默认是mark</span></td><td key=5></td></tr><tr key=0-1-4-11><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> triggerPrice</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">委托触发价格</span></td><td key=5></td></tr><tr key=0-1-4-12><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> orderPrice</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">委托价格</span></td><td key=5></td></tr><tr key=0-1-4-13><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> baseCurrency</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">基本货币</span></td><td key=5></td></tr><tr key=0-1-4-14><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> type</span></td><td key=1><span>integer</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">触发单类型, 1:计划委托;2:仓位止盈;3:仓位止损;4:订单止盈;5:订单止损;</span></td><td key=5></td></tr><tr key=0-1-4-15><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> status</span></td><td key=1><span>integer</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">订单状态：1-INACTIVATED，2-PENDING，3-TRIGGERING，4-SUCCESSFUL，5-CANCELED，6-FAILED</span></td><td key=5></td></tr><tr key=0-1-4-16><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> currentPrice</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">下单时的价格，如果是选择按标记价格触发，就是实时标记价格，如果是选择按最新价触发，就是实时成交价格，如果选择按指数价触发，就是实时指数价。</span></td><td key=5></td></tr><tr key=0-2><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> code</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">错误码</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1</span></p></td></tr><tr key=0-3><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> ts</span></td><td key=1><span>integer</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">系统时间</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1660101471921</span></p></td></tr><tr key=0-4><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> traceId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr>
               </tbody>
              </table>
            
## 计划委托下单
<a id=计划委托下单2729> </a>
### 基本信息

**Path：** /v1/trade/web/stopOrders

**Method：** POST

**接口描述：**
<p></p>

### 请求参数
**Headers**

| 参数名称  | 参数值  |  是否必须 | 示例  | 备注  |
| ------------ | ------------ | ------------ | ------------ | ------------ |
| Content-Type  |  application/json | 是  |  application/json |   |
**Body**

<table>
  <thead class="ant-table-thead">
    <tr>
      <th key=name>名称</th><th key=type>类型</th><th key=required>是否必须</th><th key=default>默认值</th><th key=desc>备注</th><th key=sub>其他信息</th>
    </tr>
  </thead><tbody className="ant-table-tbody"><tr key=0-0><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> tradeType</span></td><td key=1><span>string</span></td><td key=2>必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">交易类型，正向永续：linearPerpetual，币本位:inversePerpetual--先定义永续</span></td><td key=5></td></tr><tr key=0-1><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> symbol</span></td><td key=1><span>string</span></td><td key=2>必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">交易对。常用形式为“基础货币”+“报价货币”</span></td><td key=5></td></tr><tr key=0-2><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> side</span></td><td key=1><span>string</span></td><td key=2>必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">交易方向，buy表示买，sell表示卖。</span></td><td key=5></td></tr><tr key=0-3><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> positionSide</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">持仓方向，单向持仓模式下非必填，默认且仅可填both;在双向持仓模式下必填,且仅可选择 long 或 short---只适用于合约业务</span></td><td key=5></td></tr><tr key=0-4><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> marginType</span></td><td key=1><span>string</span></td><td key=2>必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">交易模式：保证金模式：isolated：逐仓 ；cross：全仓 非保证金模式：cash：非保证金</span></td><td key=5></td></tr><tr key=0-5><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> orderType</span></td><td key=1><span>string</span></td><td key=2>必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">委托类型。可接受的值： triggerMarket（市价计划单）、triggerLimit（限价计划单）tpsl(止盈止损)----只适用于合约业务</span></td><td key=5></td></tr><tr key=0-6><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> priceType</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">开仓成交价格类型，仅对市价单和市价计划单有效。枚举类型有：marketPrice；optimalFive ，默认为marketPrice</span></td><td key=5></td></tr><tr key=0-7><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> price</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">委托价格。如果是下限价单，该参数为必填。</span></td><td key=5></td></tr><tr key=0-8><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> orderQty</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">委托数量, 如果全部止盈止损,填0即可, 如果部分止盈止损则最大为可平仓数量</span></td><td key=5></td></tr><tr key=0-9><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> tpOrdPx</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">止盈触发价格</span></td><td key=5></td></tr><tr key=0-10><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> slOrdPx</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">止损触发价格</span></td><td key=5></td></tr><tr key=0-11><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> ordPx</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">计划委托触发价格</span></td><td key=5></td></tr><tr key=0-12><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> tpTriggerPxType</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">止盈触发价格类型 last：最新价格 index：指数价格 mark：标记价格 默认为mark</span></td><td key=5></td></tr><tr key=0-13><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> slTriggerPxType</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">止损触发价格类型 last：最新价格 index：指数价格 mark：标记价格 默认为mark</span></td><td key=5></td></tr><tr key=0-14><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> triggerPxType</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">计划委托触发价格类型 last：最新价格 index：指数价格 mark：标记价格 默认为mark</span></td><td key=5></td></tr><tr key=0-15><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> timeInForce</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">gtc/ioc/fok，默认是 gtc--只适用于合约业务</span></td><td key=5></td></tr><tr key=0-16><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> slOrderQty</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">止损委托数量</span></td><td key=5></td></tr><tr key=0-17><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> tpOrderQty</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">止盈委托数量</span></td><td key=5></td></tr>
               </tbody>
              </table>
            
### 返回数据

<table>
  <thead class="ant-table-thead">
    <tr>
      <th key=name>名称</th><th key=type>类型</th><th key=required>是否必须</th><th key=default>默认值</th><th key=desc>备注</th><th key=sub>其他信息</th>
    </tr>
  </thead><tbody className="ant-table-tbody"><tr key=0-0><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> msg</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">请求结果描述。请求成功返回成功描述。发生错误返回具体错误描述。</span></td><td key=5></td></tr><tr key=0-1><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> data</span></td><td key=1><span>object []</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">数据</span></td><td key=5><p key=3><span style="font-weight: '700'">item 类型: </span><span>object</span></p></td></tr><tr key=0-1-0><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> clOrdId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">用户自定义订单ID</span></td><td key=5></td></tr><tr key=0-1-1><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> createTime</span></td><td key=1><span>integer</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">订单创建时间</span></td><td key=5></td></tr><tr key=0-1-2><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> stopOrderId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">计划委托订单id</span></td><td key=5></td></tr><tr key=0-2><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> code</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">错误码</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1</span></p></td></tr><tr key=0-3><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> ts</span></td><td key=1><span>integer</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">系统时间</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1660101471921</span></p></td></tr><tr key=0-4><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> traceId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr>
               </tbody>
              </table>
            
## 计划委托撤单
<a id=计划委托撤单2729> </a>
### 基本信息

**Path：** /v1/trade/web/stopOrders/cancel

**Method：** POST

**接口描述：**
<p></p>

### 请求参数
**Headers**

| 参数名称  | 参数值  |  是否必须 | 示例  | 备注  |
| ------------ | ------------ | ------------ | ------------ | ------------ |
| Content-Type  |  application/json | 是  |  application/json |   |
**Body**

<table>
  <thead class="ant-table-thead">
    <tr>
      <th key=name>名称</th><th key=type>类型</th><th key=required>是否必须</th><th key=default>默认值</th><th key=desc>备注</th><th key=sub>其他信息</th>
    </tr>
  </thead><tbody className="ant-table-tbody"><tr key=0-0><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> stopOrderId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">要撤消的订单的订单 ID，单个撤销</span></td><td key=5></td></tr><tr key=0-1><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> tradeType</span></td><td key=1><span>string</span></td><td key=2>必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">交易类型，正向永续：linearPerpetual，币本位:inversePerpetual--先定义永续</span></td><td key=5></td></tr><tr key=0-2><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> symbol</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">交易对</span></td><td key=5></td></tr>
               </tbody>
              </table>
            
### 返回数据

<table>
  <thead class="ant-table-thead">
    <tr>
      <th key=name>名称</th><th key=type>类型</th><th key=required>是否必须</th><th key=default>默认值</th><th key=desc>备注</th><th key=sub>其他信息</th>
    </tr>
  </thead><tbody className="ant-table-tbody"><tr key=0-0><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> msg</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">请求结果描述。请求成功返回成功描述。发生错误返回具体错误描述。</span></td><td key=5></td></tr><tr key=0-1><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> data</span></td><td key=1><span>object []</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">数据</span></td><td key=5><p key=3><span style="font-weight: '700'">item 类型: </span><span>object</span></p></td></tr><tr key=0-1-0><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> clOrdId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">自定义订单id</span></td><td key=5></td></tr><tr key=0-1-1><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> orderId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">要撤消的订单的订单 ID</span></td><td key=5></td></tr><tr key=0-2><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> code</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">错误码</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1</span></p></td></tr><tr key=0-3><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> ts</span></td><td key=1><span>integer</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">系统时间</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1660101471921</span></p></td></tr><tr key=0-4><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> traceId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr>
               </tbody>
              </table>
            
# openApiV3 订单

## 单个下单
<a id=单个下单2734> </a>
### 基本信息

**Path：** /openapi/v3/trade/order

**Method：** POST

**接口描述：**
<p></p>

### 请求参数
**Headers**

| 参数名称  | 参数值  |  是否必须 | 示例  | 备注  |
| ------------ | ------------ | ------------ | ------------ | ------------ |
| Content-Type  |  application/json | 是  |  application/json |   |
**Body**

<table>
  <thead class="ant-table-thead">
    <tr>
      <th key=name>名称</th><th key=type>类型</th><th key=required>是否必须</th><th key=default>默认值</th><th key=desc>备注</th><th key=sub>其他信息</th>
    </tr>
  </thead><tbody className="ant-table-tbody"><tr key=0-0><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> instType</span></td><td key=1><span>string</span></td><td key=2>必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">交易类型， SPOT,SWAP</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>SWAP</span></p></td></tr><tr key=0-1><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> instId</span></td><td key=1><span>string</span></td><td key=2>必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">产品ID</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>BTC_USDT</span></p></td></tr><tr key=0-2><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> clOrdId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">用户自定义订单ID 字母（区分大小写）与数字的组合，可以是纯字母、纯数字且长度要在1-32位之间</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>123456</span></p></td></tr><tr key=0-3><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> side</span></td><td key=1><span>string</span></td><td key=2>必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">交易方向，1:buy, 2:sell, buy表示买，sell表示卖。</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>buy</span></p></td></tr><tr key=0-4><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> ordType</span></td><td key=1><span>string</span></td><td key=2>必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">订单类型</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>limit</span></p></td></tr><tr key=0-5><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> sz</span></td><td key=1><span>string</span></td><td key=2>必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">委托数量</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1</span></p></td></tr><tr key=0-6><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> px</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">委托价格。仅适用于limit、post_only、fok、ioc</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>20000</span></p></td></tr><tr key=0-7><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> tgtCcy</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">市价单委托数量sz的单位，仅适用于币币市价订单
base_ccy: 交易货币
quote_ccy：计价货币
买单默认 quote_ccy， 卖单默认base_ccy</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>quote_ccy</span></p></td></tr><tr key=0-8><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> stpId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">自成交保护ID。来自同一个母账户配着同一个ID的订单不能自成交
用户自定义1<=x<=999999999的整数
默认取账户ID, 即同一账户（子账户）内不可以自成交</span></td><td key=5></td></tr><tr key=0-9><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> stpMode</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">自成交保护模式
no_cancel, 支持自成交
cancel_maker，当发生自成交时，撤销maker单
cancel_taker, 当发生自成交时，撤销taker单
cancel_both,当发生自成交时，同时撤销taker和maker单
cancel both不支持FOK</span></td><td key=5></td></tr><tr key=0-10><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> tag</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">订单标签
字母（区分大小写）与数字的组合，可以是纯字母、纯数字，且长度在1-16位之间。*</span></td><td key=5></td></tr><tr key=0-11><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> ccy</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">保证金币种</span></td><td key=5></td></tr><tr key=0-12><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> posSide</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">持仓方向
`long` 多仓
`short` 空仓</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>long</span></p></td></tr><tr key=0-13><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> tpTriggerPxType</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">止盈触发价类型	*
枚举: last,index,mark

枚举备注: last :市场价格:盘内最新成交价格（默认） index :指数价格 mark :标记价格

mock: @pick(["last","index","mark"])</span></td><td key=5></td></tr><tr key=0-14><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> tpTriggerPx</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">止盈触发价，如果填写此参数，必须填写 止盈委托价	*</span></td><td key=5></td></tr><tr key=0-15><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> tpOrdPx</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">止盈委托价，如果填写此参数，必须填写 止盈触发价
委托价格 >= 0, 执行限价止盈
委托价格为-1时, 执行市价止盈</span></td><td key=5></td></tr><tr key=0-16><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> slTriggerPx</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">止损触发价，如果填写此参数，必须填写 止损委托价	*</span></td><td key=5></td></tr><tr key=0-17><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> slOrdPx</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">止损委托价，如果填写此参数，必须填写 止损触发价
委托价格 >= 0, 执行限价止盈
委托价格为-1时, 执行市价止盈</span></td><td key=5></td></tr><tr key=0-18><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> slTriggerPxType</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">止损触发价类型
枚举: last,index,mark

枚举备注: last :市场价格:盘内最新成交价格（默认） index :指数价格 mark :标记价格

mock: @pick(["last","index","mark"])</span></td><td key=5></td></tr><tr key=0-19><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> tpAlgoClOrdId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">下单附带止盈时，客户自定义的策略订单ID	*</span></td><td key=5></td></tr><tr key=0-20><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> slAlgoClOrdId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">下单附带止损时，客户自定义的策略订单ID	*</span></td><td key=5></td></tr><tr key=0-21><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> lever</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">杠杆倍数</span></td><td key=5></td></tr><tr key=0-22><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> orderResponseType</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">订单是否同步返回
FULL：同步返回
RESULT: 异步返回</span></td><td key=5></td></tr>
               </tbody>
              </table>
            
### 返回数据

<table>
  <thead class="ant-table-thead">
    <tr>
      <th key=name>名称</th><th key=type>类型</th><th key=required>是否必须</th><th key=default>默认值</th><th key=desc>备注</th><th key=sub>其他信息</th>
    </tr>
  </thead><tbody className="ant-table-tbody"><tr key=0-0><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> msg</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">请求结果描述。请求成功返回成功描述。发生错误返回具体错误描述。</span></td><td key=5></td></tr><tr key=0-1><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> data</span></td><td key=1><span>object</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">数据</span></td><td key=5></td></tr><tr key=0-1-0><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> sCode</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3>0</td><td key=4><span style="white-space: pre-wrap">此事件执行结果的code，0代表成功</span></td><td key=5></td></tr><tr key=0-1-1><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> sMsg</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">此事件执行失败或成功时的msg</span></td><td key=5></td></tr><tr key=0-1-2><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> ordId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">订单号</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>12345678901234567890</span></p></td></tr><tr key=0-1-3><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> clOrdId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">客户端ID</span></td><td key=5></td></tr><tr key=0-1-4><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> tag</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">订单标签</span></td><td key=5></td></tr><tr key=0-1-5><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> algoOrderResps</span></td><td key=1><span>object []</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5><p key=3><span style="font-weight: '700'">item 类型: </span><span>object</span></p></td></tr><tr key=0-1-5-0><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> sCode</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3>0</td><td key=4><span style="white-space: pre-wrap">此事件执行结果的code，0代表成功</span></td><td key=5></td></tr><tr key=0-1-5-1><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> sMsg</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">此事件执行失败或成功时的msg</span></td><td key=5></td></tr><tr key=0-1-5-2><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> algoId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">订单号</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>12345678901234567890</span></p></td></tr><tr key=0-1-5-3><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> algoClOrdId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">客户端ID</span></td><td key=5></td></tr><tr key=0-1-5-4><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> algoId2</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">订单ID</span></td><td key=5></td></tr><tr key=0-1-5-5><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> algoClOrdId2</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">客户自定义订单ID</span></td><td key=5></td></tr><tr key=0-2><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> code</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">错误码</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1</span></p></td></tr><tr key=0-3><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> ts</span></td><td key=1><span>integer</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">系统时间</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1660101471921</span></p></td></tr><tr key=0-4><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> traceId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr>
               </tbody>
              </table>
            
## 单个撤单
<a id=单个撤单2734> </a>
### 基本信息

**Path：** /openapi/v3/trade/cancel-order

**Method：** POST

**接口描述：**
<p></p>

### 请求参数
**Headers**

| 参数名称  | 参数值  |  是否必须 | 示例  | 备注  |
| ------------ | ------------ | ------------ | ------------ | ------------ |
| Content-Type  |  application/json | 是  |  application/json |   |
**Body**

<table>
  <thead class="ant-table-thead">
    <tr>
      <th key=name>名称</th><th key=type>类型</th><th key=required>是否必须</th><th key=default>默认值</th><th key=desc>备注</th><th key=sub>其他信息</th>
    </tr>
  </thead><tbody className="ant-table-tbody"><tr key=0-0><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> instType</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">交易类型， SPOT,SWAP</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>SWAP</span></p></td></tr><tr key=0-1><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> instId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">产品ID</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>BTC_USDT</span></p></td></tr><tr key=0-2><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> clOrdId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">用户自定义订单ID 字母（区分大小写）与数字的组合，可以是纯字母、纯数字且长度要在1-32位之间</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>123456</span></p></td></tr><tr key=0-3><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> ordId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">订单ID</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>123456</span></p></td></tr><tr key=0-4><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> orderResponseType</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">订单是否同步返回
FULL：同步返回
RESULT: 异步返回</span></td><td key=5></td></tr>
               </tbody>
              </table>
            
### 返回数据

<table>
  <thead class="ant-table-thead">
    <tr>
      <th key=name>名称</th><th key=type>类型</th><th key=required>是否必须</th><th key=default>默认值</th><th key=desc>备注</th><th key=sub>其他信息</th>
    </tr>
  </thead><tbody className="ant-table-tbody"><tr key=0-0><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> msg</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">请求结果描述。请求成功返回成功描述。发生错误返回具体错误描述。</span></td><td key=5></td></tr><tr key=0-1><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> data</span></td><td key=1><span>object</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">数据</span></td><td key=5></td></tr><tr key=0-1-0><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> sCode</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3>0</td><td key=4><span style="white-space: pre-wrap">此事件执行结果的code，0代表成功</span></td><td key=5></td></tr><tr key=0-1-1><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> sMsg</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">此事件执行失败或成功时的msg</span></td><td key=5></td></tr><tr key=0-1-2><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> ordId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">订单号</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>12345678901234567890</span></p></td></tr><tr key=0-1-3><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> clOrdId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">客户端ID</span></td><td key=5></td></tr><tr key=0-1-4><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> tag</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">订单标签</span></td><td key=5></td></tr><tr key=0-1-5><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> algoOrderResps</span></td><td key=1><span>object []</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5><p key=3><span style="font-weight: '700'">item 类型: </span><span>object</span></p></td></tr><tr key=0-1-5-0><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> sCode</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3>0</td><td key=4><span style="white-space: pre-wrap">此事件执行结果的code，0代表成功</span></td><td key=5></td></tr><tr key=0-1-5-1><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> sMsg</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">此事件执行失败或成功时的msg</span></td><td key=5></td></tr><tr key=0-1-5-2><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> algoId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">订单号</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>12345678901234567890</span></p></td></tr><tr key=0-1-5-3><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> algoClOrdId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">客户端ID</span></td><td key=5></td></tr><tr key=0-1-5-4><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> algoId2</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">订单ID</span></td><td key=5></td></tr><tr key=0-1-5-5><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> algoClOrdId2</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">客户自定义订单ID</span></td><td key=5></td></tr><tr key=0-2><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> code</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">错误码</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1</span></p></td></tr><tr key=0-3><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> ts</span></td><td key=1><span>integer</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">系统时间</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1660101471921</span></p></td></tr><tr key=0-4><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> traceId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr>
               </tbody>
              </table>
            
## 批量下单
<a id=批量下单2734> </a>
### 基本信息

**Path：** /openapi/v3/trade/batch-orders

**Method：** POST

**接口描述：**
<p></p>

### 请求参数
**Headers**

| 参数名称  | 参数值  |  是否必须 | 示例  | 备注  |
| ------------ | ------------ | ------------ | ------------ | ------------ |
| Content-Type  |  application/json | 是  |  application/json |   |
**Body**

<table>
  <thead class="ant-table-thead">
    <tr>
      <th key=name>名称</th><th key=type>类型</th><th key=required>是否必须</th><th key=default>默认值</th><th key=desc>备注</th><th key=sub>其他信息</th>
    </tr>
  </thead><tbody className="ant-table-tbody"><tr key=0-0><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> data</span></td><td key=1><span>object []</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">数据</span></td><td key=5><p key=3><span style="font-weight: '700'">item 类型: </span><span>object</span></p></td></tr><tr key=0-0-0><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> instType</span></td><td key=1><span>string</span></td><td key=2>必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">交易类型， SPOT,SWAP</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>SWAP</span></p></td></tr><tr key=0-0-1><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> instId</span></td><td key=1><span>string</span></td><td key=2>必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">产品ID</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>BTC_USDT</span></p></td></tr><tr key=0-0-2><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> clOrdId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">用户自定义订单ID 字母（区分大小写）与数字的组合，可以是纯字母、纯数字且长度要在1-32位之间</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>123456</span></p></td></tr><tr key=0-0-3><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> side</span></td><td key=1><span>string</span></td><td key=2>必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">交易方向，1:buy, 2:sell, buy表示买，sell表示卖。</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>buy</span></p></td></tr><tr key=0-0-4><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> ordType</span></td><td key=1><span>string</span></td><td key=2>必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">订单类型</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>limit</span></p></td></tr><tr key=0-0-5><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> sz</span></td><td key=1><span>string</span></td><td key=2>必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">委托数量</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1</span></p></td></tr><tr key=0-0-6><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> px</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">委托价格。仅适用于limit、post_only、fok、ioc</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>20000</span></p></td></tr><tr key=0-0-7><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> tgtCcy</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">市价单委托数量sz的单位，仅适用于币币市价订单
base_ccy: 交易货币
quote_ccy：计价货币
买单默认 quote_ccy， 卖单默认base_ccy</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>quote_ccy</span></p></td></tr><tr key=0-0-8><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> stpId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">自成交保护ID。来自同一个母账户配着同一个ID的订单不能自成交
用户自定义1<=x<=999999999的整数
默认取账户ID, 即同一账户（子账户）内不可以自成交</span></td><td key=5></td></tr><tr key=0-0-9><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> stpMode</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">自成交保护模式
no_cancel, 支持自成交
cancel_maker，当发生自成交时，撤销maker单
cancel_taker, 当发生自成交时，撤销taker单
cancel_both,当发生自成交时，同时撤销taker和maker单
cancel both不支持FOK</span></td><td key=5></td></tr><tr key=0-0-10><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> tag</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">订单标签
字母（区分大小写）与数字的组合，可以是纯字母、纯数字，且长度在1-16位之间。*</span></td><td key=5></td></tr><tr key=0-0-11><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> ccy</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">保证金币种</span></td><td key=5></td></tr><tr key=0-0-12><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> posSide</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">持仓方向
`long` 多仓
`short` 空仓</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>long</span></p></td></tr><tr key=0-0-13><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> tpTriggerPxType</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">止盈触发价类型	*
枚举: last,index,mark

枚举备注: last :市场价格:盘内最新成交价格（默认） index :指数价格 mark :标记价格

mock: @pick(["last","index","mark"])</span></td><td key=5></td></tr><tr key=0-0-14><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> tpTriggerPx</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">止盈触发价，如果填写此参数，必须填写 止盈委托价	*</span></td><td key=5></td></tr><tr key=0-0-15><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> tpOrdPx</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">止盈委托价，如果填写此参数，必须填写 止盈触发价
委托价格 >= 0, 执行限价止盈
委托价格为-1时, 执行市价止盈</span></td><td key=5></td></tr><tr key=0-0-16><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> slTriggerPx</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">止损触发价，如果填写此参数，必须填写 止损委托价	*</span></td><td key=5></td></tr><tr key=0-0-17><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> slOrdPx</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">止损委托价，如果填写此参数，必须填写 止损触发价
委托价格 >= 0, 执行限价止盈
委托价格为-1时, 执行市价止盈</span></td><td key=5></td></tr><tr key=0-0-18><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> slTriggerPxType</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">止损触发价类型
枚举: last,index,mark

枚举备注: last :市场价格:盘内最新成交价格（默认） index :指数价格 mark :标记价格

mock: @pick(["last","index","mark"])</span></td><td key=5></td></tr><tr key=0-0-19><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> tpAlgoClOrdId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">下单附带止盈时，客户自定义的策略订单ID	*</span></td><td key=5></td></tr><tr key=0-0-20><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> slAlgoClOrdId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">下单附带止损时，客户自定义的策略订单ID	*</span></td><td key=5></td></tr><tr key=0-0-21><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> lever</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">杠杆倍数</span></td><td key=5></td></tr><tr key=0-0-22><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> orderResponseType</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">订单是否同步返回
FULL：同步返回
RESULT: 异步返回</span></td><td key=5></td></tr><tr key=0-1><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> startTime</span></td><td key=1><span>integer</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">访问时间</span></td><td key=5></td></tr>
               </tbody>
              </table>
            
### 返回数据

<table>
  <thead class="ant-table-thead">
    <tr>
      <th key=name>名称</th><th key=type>类型</th><th key=required>是否必须</th><th key=default>默认值</th><th key=desc>备注</th><th key=sub>其他信息</th>
    </tr>
  </thead><tbody className="ant-table-tbody"><tr key=0-0><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> msg</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">请求结果描述。请求成功返回成功描述。发生错误返回具体错误描述。</span></td><td key=5></td></tr><tr key=0-1><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> data</span></td><td key=1><span>object []</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">数据</span></td><td key=5><p key=3><span style="font-weight: '700'">item 类型: </span><span>object</span></p></td></tr><tr key=0-1-0><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> sCode</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3>0</td><td key=4><span style="white-space: pre-wrap">此事件执行结果的code，0代表成功</span></td><td key=5></td></tr><tr key=0-1-1><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> sMsg</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">此事件执行失败或成功时的msg</span></td><td key=5></td></tr><tr key=0-1-2><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> ordId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">订单号</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>12345678901234567890</span></p></td></tr><tr key=0-1-3><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> clOrdId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">客户端ID</span></td><td key=5></td></tr><tr key=0-1-4><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> tag</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">订单标签</span></td><td key=5></td></tr><tr key=0-1-5><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> algoOrderResps</span></td><td key=1><span>object []</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5><p key=3><span style="font-weight: '700'">item 类型: </span><span>object</span></p></td></tr><tr key=0-1-5-0><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> sCode</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3>0</td><td key=4><span style="white-space: pre-wrap">此事件执行结果的code，0代表成功</span></td><td key=5></td></tr><tr key=0-1-5-1><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> sMsg</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">此事件执行失败或成功时的msg</span></td><td key=5></td></tr><tr key=0-1-5-2><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> algoId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">订单号</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>12345678901234567890</span></p></td></tr><tr key=0-1-5-3><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> algoClOrdId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">客户端ID</span></td><td key=5></td></tr><tr key=0-1-5-4><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> algoId2</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">订单ID</span></td><td key=5></td></tr><tr key=0-1-5-5><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> algoClOrdId2</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">客户自定义订单ID</span></td><td key=5></td></tr><tr key=0-2><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> code</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">错误码</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1</span></p></td></tr><tr key=0-3><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> ts</span></td><td key=1><span>integer</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">系统时间</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1660101471921</span></p></td></tr><tr key=0-4><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> traceId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr>
               </tbody>
              </table>
            
## 批量撤单
<a id=批量撤单2734> </a>
### 基本信息

**Path：** /openapi/v3/trade/cancel-batch-orders

**Method：** POST

**接口描述：**
<p></p>

### 请求参数
**Headers**

| 参数名称  | 参数值  |  是否必须 | 示例  | 备注  |
| ------------ | ------------ | ------------ | ------------ | ------------ |
| Content-Type  |  application/json | 是  |  application/json |   |
**Body**

<table>
  <thead class="ant-table-thead">
    <tr>
      <th key=name>名称</th><th key=type>类型</th><th key=required>是否必须</th><th key=default>默认值</th><th key=desc>备注</th><th key=sub>其他信息</th>
    </tr>
  </thead><tbody className="ant-table-tbody"><tr key=0-0><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> data</span></td><td key=1><span>object []</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">数据</span></td><td key=5><p key=3><span style="font-weight: '700'">item 类型: </span><span>object</span></p></td></tr><tr key=0-0-0><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> instType</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">交易类型， SPOT,SWAP</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>SWAP</span></p></td></tr><tr key=0-0-1><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> instId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">产品ID</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>BTC_USDT</span></p></td></tr><tr key=0-0-2><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> clOrdId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">用户自定义订单ID 字母（区分大小写）与数字的组合，可以是纯字母、纯数字且长度要在1-32位之间</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>123456</span></p></td></tr><tr key=0-0-3><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> ordId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">订单ID</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>123456</span></p></td></tr><tr key=0-0-4><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> orderResponseType</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">订单是否同步返回
FULL：同步返回
RESULT: 异步返回</span></td><td key=5></td></tr><tr key=0-1><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> startTime</span></td><td key=1><span>integer</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">访问时间</span></td><td key=5></td></tr>
               </tbody>
              </table>
            
### 返回数据

<table>
  <thead class="ant-table-thead">
    <tr>
      <th key=name>名称</th><th key=type>类型</th><th key=required>是否必须</th><th key=default>默认值</th><th key=desc>备注</th><th key=sub>其他信息</th>
    </tr>
  </thead><tbody className="ant-table-tbody"><tr key=0-0><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> msg</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">请求结果描述。请求成功返回成功描述。发生错误返回具体错误描述。</span></td><td key=5></td></tr><tr key=0-1><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> data</span></td><td key=1><span>object []</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">数据</span></td><td key=5><p key=3><span style="font-weight: '700'">item 类型: </span><span>object</span></p></td></tr><tr key=0-1-0><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> sCode</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3>0</td><td key=4><span style="white-space: pre-wrap">此事件执行结果的code，0代表成功</span></td><td key=5></td></tr><tr key=0-1-1><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> sMsg</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">此事件执行失败或成功时的msg</span></td><td key=5></td></tr><tr key=0-1-2><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> ordId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">订单号</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>12345678901234567890</span></p></td></tr><tr key=0-1-3><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> clOrdId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">客户端ID</span></td><td key=5></td></tr><tr key=0-1-4><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> tag</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">订单标签</span></td><td key=5></td></tr><tr key=0-1-5><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> algoOrderResps</span></td><td key=1><span>object []</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5><p key=3><span style="font-weight: '700'">item 类型: </span><span>object</span></p></td></tr><tr key=0-1-5-0><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> sCode</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3>0</td><td key=4><span style="white-space: pre-wrap">此事件执行结果的code，0代表成功</span></td><td key=5></td></tr><tr key=0-1-5-1><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> sMsg</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">此事件执行失败或成功时的msg</span></td><td key=5></td></tr><tr key=0-1-5-2><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> algoId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">订单号</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>12345678901234567890</span></p></td></tr><tr key=0-1-5-3><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> algoClOrdId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">客户端ID</span></td><td key=5></td></tr><tr key=0-1-5-4><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> algoId2</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">订单ID</span></td><td key=5></td></tr><tr key=0-1-5-5><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> algoClOrdId2</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">客户自定义订单ID</span></td><td key=5></td></tr><tr key=0-2><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> code</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">错误码</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1</span></p></td></tr><tr key=0-3><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> ts</span></td><td key=1><span>integer</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">系统时间</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1660101471921</span></p></td></tr><tr key=0-4><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> traceId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr>
               </tbody>
              </table>
            
# openApiV3 账户及仓位

## GET 查看持仓信息
<a id=GET 查看持仓信息2739> </a>
### 基本信息

**Path：** /openapi/v3/account/positions

**Method：** GET

**接口描述：**
<p>获取该账户下拥有实际持仓的信息。账户为买卖模式会显示净持仓（net），账户为开平仓模式下会分别返回开多（long）或开空（short）的仓位。
按照仓位创建时间倒序排列。</p>

### 请求参数
**Query**

| 参数名称  |  是否必须 | 示例  | 备注  |
| ------------ | ------------ | ------------ | ------------ |
| instType | 否  |   |  产品类型 [com.qhxc.global.trade.open.apiv3.enmus.InstrumentTypeEnum#name]<br/>SPOT :现货<br/>SWAP :永续合约 |
| instId | 否  |   |  产品ID，如BTC-USD-200927 |
| posId | 否  |   |  持仓ID<br/>                 支持多个posId查询（不超过20个）。<br/>                 存在有效期的属性，自最近一次平仓算起，满30天 posId 以及整个仓位会被清除。 |

### 返回数据

<table>
  <thead class="ant-table-thead">
    <tr>
      <th key=name>名称</th><th key=type>类型</th><th key=required>是否必须</th><th key=default>默认值</th><th key=desc>备注</th><th key=sub>其他信息</th>
    </tr>
  </thead><tbody className="ant-table-tbody"><tr key=0-0><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> msg</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">请求结果描述。请求成功返回成功描述。发生错误返回具体错误描述。</span></td><td key=5></td></tr><tr key=0-1><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> data</span></td><td key=1><span>object []</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">数据</span></td><td key=5><p key=3><span style="font-weight: '700'">item 类型: </span><span>object</span></p></td></tr><tr key=0-1-0><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> instType</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr><tr key=0-1-1><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> instId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr><tr key=0-1-2><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> lever</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr><tr key=0-1-3><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> posId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr><tr key=0-1-4><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> uTime</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr><tr key=0-1-5><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> cTime</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr><tr key=0-1-6><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> posSide</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr><tr key=0-1-7><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> pos</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">持仓数量</span></td><td key=5></td></tr><tr key=0-1-8><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> availPos</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">可平仓数量</span></td><td key=5></td></tr><tr key=0-1-9><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> avgPx</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">开仓平均价 ??</span></td><td key=5></td></tr><tr key=0-1-10><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> uPnl</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">未实现盈亏（以标记价格计算）</span></td><td key=5></td></tr><tr key=0-1-11><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> uPnlRatio</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">未实现收益率（以标记价格计算）</span></td><td key=5></td></tr><tr key=0-1-12><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> liqPx</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">预估强平价</span></td><td key=5></td></tr><tr key=0-1-13><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> markPx</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">最新标记价格</span></td><td key=5></td></tr><tr key=0-1-14><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> imr</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">初始保证金</span></td><td key=5></td></tr><tr key=0-1-15><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> mmr</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">维持保证金</span></td><td key=5></td></tr><tr key=0-1-16><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> mgnRatio</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">保证金率(即风险率)</span></td><td key=5></td></tr><tr key=0-1-17><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> adl</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">信号区
分为5档，从1到5，数字越小代表adl强度越弱</span></td><td key=5></td></tr><tr key=0-1-18><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> ccy</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">占用保证金币种</span></td><td key=5></td></tr><tr key=0-1-19><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> lastPx</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">最新成交价</span></td><td key=5></td></tr><tr key=0-1-20><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> idxPx</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">最新指数价格</span></td><td key=5></td></tr><tr key=0-2><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> code</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">错误码</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1</span></p></td></tr><tr key=0-3><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> ts</span></td><td key=1><span>integer</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">系统时间</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1660101471921</span></p></td></tr><tr key=0-4><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> traceId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr>
               </tbody>
              </table>
            
## GET 查看账户余额
<a id=GET 查看账户余额2739> </a>
### 基本信息

**Path：** /openapi/v3/account/balance

**Method：** GET

**接口描述：**
<p>获取交易账户中资金余额信息。</p>

### 请求参数
**Query**

| 参数名称  |  是否必须 | 示例  | 备注  |
| ------------ | ------------ | ------------ | ------------ |
| ccy | 否  |   |  币种，如 BTC,ETH 支持多币种查询（不超过20个），币种之间半角逗号分隔 |

### 返回数据

<table>
  <thead class="ant-table-thead">
    <tr>
      <th key=name>名称</th><th key=type>类型</th><th key=required>是否必须</th><th key=default>默认值</th><th key=desc>备注</th><th key=sub>其他信息</th>
    </tr>
  </thead><tbody className="ant-table-tbody"><tr key=0-0><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> msg</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">请求结果描述。请求成功返回成功描述。发生错误返回具体错误描述。</span></td><td key=5></td></tr><tr key=0-1><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> data</span></td><td key=1><span>object []</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">数据</span></td><td key=5><p key=3><span style="font-weight: '700'">item 类型: </span><span>object</span></p></td></tr><tr key=0-1-0><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> uTime</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">更新时间，Unix时间戳的毫秒数格式，如 1597026383085</span></td><td key=5></td></tr><tr key=0-1-1><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> totalEq</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">总权益(折合)</span></td><td key=5></td></tr><tr key=0-1-2><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> ordFroz</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">全仓挂单占用保证金(折合)</span></td><td key=5></td></tr><tr key=0-1-3><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> imrEq</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">挂单占用保证金(折合)</span></td><td key=5></td></tr><tr key=0-1-4><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> mmrEq</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">维持保证金(折合)</span></td><td key=5></td></tr><tr key=0-1-5><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> mgnRatio</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">保证金率</span></td><td key=5></td></tr><tr key=0-1-6><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> details</span></td><td key=1><span>object []</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">各币种资产详细信息</span></td><td key=5><p key=3><span style="font-weight: '700'">item 类型: </span><span>object</span></p></td></tr><tr key=0-1-6-0><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> uTime</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">更新时间，Unix时间戳的毫秒数格式，如 1597026383085</span></td><td key=5></td></tr><tr key=0-1-6-1><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> ccy</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">币种</span></td><td key=5></td></tr><tr key=0-1-6-2><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> eq</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">总权益</span></td><td key=5></td></tr><tr key=0-1-6-3><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> bal</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">币种余额 ??</span></td><td key=5></td></tr><tr key=0-1-6-4><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> availEq</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">币种可用(折合)</span></td><td key=5></td></tr><tr key=0-1-6-5><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> avail</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">币种可用</span></td><td key=5></td></tr><tr key=0-1-6-6><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> frozen</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">币种持仓占用??
「已废弃」</span></td><td key=5></td></tr><tr key=0-1-6-7><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> imr</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">初始保证金</span></td><td key=5></td></tr><tr key=0-1-6-8><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> mmr</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">维持保证金</span></td><td key=5></td></tr><tr key=0-1-6-9><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> ordFroz</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">币种委托占用??</span></td><td key=5></td></tr><tr key=0-1-6-10><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> uPnl</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">未实现盈亏</span></td><td key=5></td></tr><tr key=0-1-6-11><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> mgnRatio</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">风险率</span></td><td key=5></td></tr><tr key=0-2><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> code</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">错误码</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1</span></p></td></tr><tr key=0-3><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> ts</span></td><td key=1><span>integer</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">系统时间</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1660101471921</span></p></td></tr><tr key=0-4><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> traceId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr>
               </tbody>
              </table>
            
## GET 获取杠杆倍数
<a id=GET 获取杠杆倍数2739> </a>
### 基本信息

**Path：** /openapi/v3/account/leverage-info

**Method：** GET

**接口描述：**
<p></p>

### 请求参数
**Query**

| 参数名称  |  是否必须 | 示例  | 备注  |
| ------------ | ------------ | ------------ | ------------ |
| instId | 是  |   |  产品ID，如BTC-USD-200927 |
| marginType | 否  |   |   |

### 返回数据

<table>
  <thead class="ant-table-thead">
    <tr>
      <th key=name>名称</th><th key=type>类型</th><th key=required>是否必须</th><th key=default>默认值</th><th key=desc>备注</th><th key=sub>其他信息</th>
    </tr>
  </thead><tbody className="ant-table-tbody"><tr key=0-0><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> msg</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">请求结果描述。请求成功返回成功描述。发生错误返回具体错误描述。</span></td><td key=5></td></tr><tr key=0-1><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> data</span></td><td key=1><span>object []</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">数据</span></td><td key=5><p key=3><span style="font-weight: '700'">item 类型: </span><span>object</span></p></td></tr><tr key=0-1-0><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> instId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">必填 产品id</span></td><td key=5></td></tr><tr key=0-1-1><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> lever</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">必填 杠杆倍数</span></td><td key=5></td></tr><tr key=0-1-2><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> mgnMode</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">非必填 模式 全逐：all  全仓：cross  逐仓：isolated, 默认all</span></td><td key=5></td></tr><tr key=0-1-3><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> posSide</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">不填</span></td><td key=5></td></tr><tr key=0-1-4><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> ccy</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">不填</span></td><td key=5></td></tr><tr key=0-2><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> code</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">错误码</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1</span></p></td></tr><tr key=0-3><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> ts</span></td><td key=1><span>integer</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">系统时间</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1660101471921</span></p></td></tr><tr key=0-4><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> traceId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr>
               </tbody>
              </table>
            
## getTradeFee
<a id=getTradeFee2739> </a>
### 基本信息

**Path：** /openapi/v3/account/trade-fee

**Method：** GET

**接口描述：**


### 请求参数
**Query**

| 参数名称  |  是否必须 | 示例  | 备注  |
| ------------ | ------------ | ------------ | ------------ |
| instType | 是  |   |   |
| instId | 否  |   |   |
| uly | 否  |   |   |
| instFamily | 否  |   |   |

### 返回数据

<table>
  <thead class="ant-table-thead">
    <tr>
      <th key=name>名称</th><th key=type>类型</th><th key=required>是否必须</th><th key=default>默认值</th><th key=desc>备注</th><th key=sub>其他信息</th>
    </tr>
  </thead><tbody className="ant-table-tbody"><tr key=0-0><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> msg</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">请求结果描述。请求成功返回成功描述。发生错误返回具体错误描述。</span></td><td key=5></td></tr><tr key=0-1><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> data</span></td><td key=1><span>object []</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">数据</span></td><td key=5><p key=3><span style="font-weight: '700'">item 类型: </span><span>object</span></p></td></tr><tr key=0-1-0><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> level</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr><tr key=0-1-1><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> taker</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr><tr key=0-1-2><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> maker</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr><tr key=0-1-3><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> takerU</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr><tr key=0-1-4><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> makerU</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr><tr key=0-1-5><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> delivery</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr><tr key=0-1-6><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> exercise</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr><tr key=0-1-7><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> instType</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr><tr key=0-1-8><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> takerUSDC</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr><tr key=0-1-9><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> makerUSDC</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr><tr key=0-1-10><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> ts</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr><tr key=0-1-11><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> instId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr><tr key=0-1-12><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> fiat</span></td><td key=1><span>object []</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5><p key=3><span style="font-weight: '700'">item 类型: </span><span>object</span></p></td></tr><tr key=0-1-12-0><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> ccy</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr><tr key=0-1-12-1><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> maker</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr><tr key=0-1-12-2><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> taker</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr><tr key=0-2><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> code</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">错误码</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1</span></p></td></tr><tr key=0-3><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> ts</span></td><td key=1><span>integer</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">系统时间</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1660101471921</span></p></td></tr><tr key=0-4><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> traceId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr>
               </tbody>
              </table>
            
## 市价仓位全平
<a id=市价仓位全平2739> </a>
### 基本信息

**Path：** /openapi/v3/account/close-position

**Method：** POST

**接口描述：**
<p>市价平掉指定交易产品的持仓</p>

### 请求参数
**Headers**

| 参数名称  | 参数值  |  是否必须 | 示例  | 备注  |
| ------------ | ------------ | ------------ | ------------ | ------------ |
| Content-Type  |  application/json | 是  |  application/json |   |
**Body**

<table>
  <thead class="ant-table-thead">
    <tr>
      <th key=name>名称</th><th key=type>类型</th><th key=required>是否必须</th><th key=default>默认值</th><th key=desc>备注</th><th key=sub>其他信息</th>
    </tr>
  </thead><tbody className="ant-table-tbody"><tr key=0-0><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> instId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">必填 产品ID</span></td><td key=5></td></tr><tr key=0-1><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> posSide</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">持仓方向</span></td><td key=5></td></tr><tr key=0-2><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> mgnMode</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">保证金模式
cross：全仓 ； isolated：逐仓</span></td><td key=5></td></tr><tr key=0-3><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> ccy</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">保证金币种</span></td><td key=5></td></tr><tr key=0-4><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> autoCxl</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">当市价全平时，平仓单是否需要自动撤销,默认为false.
false：不自动撤单 true：自动撤单</span></td><td key=5></td></tr><tr key=0-5><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> clOrdId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">客户自定义ID</span></td><td key=5></td></tr><tr key=0-6><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> tag</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">订单标签</span></td><td key=5></td></tr>
               </tbody>
              </table>
            
### 返回数据

<table>
  <thead class="ant-table-thead">
    <tr>
      <th key=name>名称</th><th key=type>类型</th><th key=required>是否必须</th><th key=default>默认值</th><th key=desc>备注</th><th key=sub>其他信息</th>
    </tr>
  </thead><tbody className="ant-table-tbody"><tr key=0-0><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> msg</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">请求结果描述。请求成功返回成功描述。发生错误返回具体错误描述。</span></td><td key=5></td></tr><tr key=0-1><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> data</span></td><td key=1><span>object</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">数据</span></td><td key=5></td></tr><tr key=0-1-0><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> posSide</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">持仓方向</span></td><td key=5></td></tr><tr key=0-1-1><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> clOrdId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">客户自定义ID</span></td><td key=5></td></tr><tr key=0-1-2><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> tag</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">订单标签</span></td><td key=5></td></tr><tr key=0-1-3><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> orders</span></td><td key=1><span>object []</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5><p key=3><span style="font-weight: '700'">item 类型: </span><span>object</span></p></td></tr><tr key=0-1-3-0><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> orderId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">订单号</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>12345678901234567890</span></p></td></tr><tr key=0-1-3-1><td key=0><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> createTime</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">创建时间</span></td><td key=5></td></tr><tr key=0-2><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> code</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">错误码</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1</span></p></td></tr><tr key=0-3><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> ts</span></td><td key=1><span>integer</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">系统时间</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1660101471921</span></p></td></tr><tr key=0-4><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> traceId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr>
               </tbody>
              </table>
            
## 设置杠杆
<a id=设置杠杆2739> </a>
### 基本信息

**Path：** /openapi/v3/account/set-leverage

**Method：** POST

**接口描述：**
<p></p>

### 请求参数
**Headers**

| 参数名称  | 参数值  |  是否必须 | 示例  | 备注  |
| ------------ | ------------ | ------------ | ------------ | ------------ |
| Content-Type  |  application/json | 是  |  application/json |   |
**Body**

<table>
  <thead class="ant-table-thead">
    <tr>
      <th key=name>名称</th><th key=type>类型</th><th key=required>是否必须</th><th key=default>默认值</th><th key=desc>备注</th><th key=sub>其他信息</th>
    </tr>
  </thead><tbody className="ant-table-tbody"><tr key=0-0><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> instId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">必填 产品id</span></td><td key=5></td></tr><tr key=0-1><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> lever</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">必填 杠杆倍数</span></td><td key=5></td></tr><tr key=0-2><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> mgnMode</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">非必填 模式 全逐：all  全仓：cross  逐仓：isolated, 默认all</span></td><td key=5></td></tr><tr key=0-3><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> posSide</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">不填</span></td><td key=5></td></tr><tr key=0-4><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> ccy</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">不填</span></td><td key=5></td></tr>
               </tbody>
              </table>
            
### 返回数据

<table>
  <thead class="ant-table-thead">
    <tr>
      <th key=name>名称</th><th key=type>类型</th><th key=required>是否必须</th><th key=default>默认值</th><th key=desc>备注</th><th key=sub>其他信息</th>
    </tr>
  </thead><tbody className="ant-table-tbody"><tr key=0-0><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> msg</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">请求结果描述。请求成功返回成功描述。发生错误返回具体错误描述。</span></td><td key=5></td></tr><tr key=0-1><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> data</span></td><td key=1><span>object</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">数据</span></td><td key=5></td></tr><tr key=0-1-0><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> instId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">必填 产品id</span></td><td key=5></td></tr><tr key=0-1-1><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> lever</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">必填 杠杆倍数</span></td><td key=5></td></tr><tr key=0-1-2><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> mgnMode</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">非必填 模式 全逐：all  全仓：cross  逐仓：isolated, 默认all</span></td><td key=5></td></tr><tr key=0-1-3><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> posSide</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">不填</span></td><td key=5></td></tr><tr key=0-1-4><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> ccy</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">不填</span></td><td key=5></td></tr><tr key=0-2><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> code</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">错误码</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1</span></p></td></tr><tr key=0-3><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> ts</span></td><td key=1><span>integer</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">系统时间</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1660101471921</span></p></td></tr><tr key=0-4><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> traceId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr>
               </tbody>
              </table>
            
# openApiV3 交易及撮合

## GET 获取未成交订单列表
<a id=GET 获取未成交订单列表2744> </a>
### 基本信息

**Path：** /openapi/v3/trade/orders-pending

**Method：** GET

**接口描述：**
<p></p>

### 请求参数
**Query**

| 参数名称  |  是否必须 | 示例  | 备注  |
| ------------ | ------------ | ------------ | ------------ |
| instType | 否  |   |  产品类型 { InstrumentTypeEnum#getName()} |
| instId | 否  |   |  产品ID，如BTC-USD-200927 |
| uly | 否  |   |  标的指数 |
| ordType | 否  |   |  订单类型 { OrderTypeEnum} |
| state | 否  |   |  订单状态 {OpenOrderStateEnum#getName()} |
| begin | 否  |   |  筛选的开始时间戳，Unix 时间戳为毫秒数格式，如 1597026383085。开区间，返回结果中不再包含次条记录 |
| end | 否  |   |  筛选的开始时间戳，Unix 时间戳为毫秒数格式，如 1597026383085。开区间，返回结果中不再包含次条记录 |
| limit | 否  |   |  返回结果的数量，最大为100，默认100条 |

### 返回数据

<table>
  <thead class="ant-table-thead">
    <tr>
      <th key=name>名称</th><th key=type>类型</th><th key=required>是否必须</th><th key=default>默认值</th><th key=desc>备注</th><th key=sub>其他信息</th>
    </tr>
  </thead><tbody className="ant-table-tbody"><tr key=0-0><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> msg</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">请求结果描述。请求成功返回成功描述。发生错误返回具体错误描述。</span></td><td key=5></td></tr><tr key=0-1><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> data</span></td><td key=1><span>object []</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">数据</span></td><td key=5><p key=3><span style="font-weight: '700'">item 类型: </span><span>object</span></p></td></tr><tr key=0-1-0><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> instType</span></td><td key=1><span>string</span></td><td key=2>必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">产品类型</span></td><td key=5><p key=2><span style="font-weight: '700'">枚举: </span><span>SPOT,SWAP</span></p><p key=3><span style="font-weight: '700'">枚举备注: </span><span>SPOT :现货
SWAP :永续合约</span></p><p key=5><span style="font-weight: '700'">mock: </span><span>@pick(["SPOT","SWAP"])</span></p></td></tr><tr key=0-1-1><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> instId</span></td><td key=1><span>string</span></td><td key=2>必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">产品ID,例如 BTC_USDT_SWAP</span></td><td key=5></td></tr><tr key=0-1-2><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> clOrdId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">客户自定义订单ID
字母（区分大小写）与数字的组合，可以是纯字母、纯数字且长度要在1-32位之间。</span></td><td key=5></td></tr><tr key=0-1-3><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> side</span></td><td key=1><span>string</span></td><td key=2>必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">订单方向
buy：买， sell：卖</span></td><td key=5></td></tr><tr key=0-1-4><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> ordType</span></td><td key=1><span>string</span></td><td key=2>必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">订单类型</span></td><td key=5><p key=2><span style="font-weight: '700'">枚举: </span><span>market,limit,post_only,fok,ioc,cancel,batch_cancel_and_limit,risk_reduce,risk_close,risk_adl</span></p><p key=3><span style="font-weight: '700'">枚举备注: </span><span>market :市价单
limit :限价单
post_only :只做maker单
fok :全部成交或立即取消
ioc :立即成交并取消剩余
cancel :取消单
batch_cancel_and_limit :批量挂单
risk_reduce :强制减仓
risk_close :强制平仓
risk_adl :ADL减仓单</span></p><p key=5><span style="font-weight: '700'">mock: </span><span>@pick(["market","limit","post_only","fok","ioc","cancel","batch_cancel_and_limit","risk_reduce","risk_close","risk_adl"])</span></p></td></tr><tr key=0-1-5><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> sz</span></td><td key=1><span>string</span></td><td key=2>必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">委托数量</span></td><td key=5></td></tr><tr key=0-1-6><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> px</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">委托价格
仅适用于limit、post_only、fok、ioc</span></td><td key=5></td></tr><tr key=0-1-7><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> tgtCcy</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">市价单委托数量sz的单位，仅适用于币币市价订单
base_ccy: 交易货币
quote_ccy：计价货币
买单默认quote_ccy， 卖单默认base_ccy</span></td><td key=5></td></tr><tr key=0-1-8><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> stpId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">自成交保护ID。来自同一个母账户配着同一个ID的订单不能自成交
用户自定义1<=x<=999999999的整数
默认取账户ID,即同一账户（子账户）内不可以自成交</span></td><td key=5></td></tr><tr key=0-1-9><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> stpMode</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">自成交保护模式
no_cancel, 支持自成交
cancel_maker，当发生自成交时，撤销maker单
cancel_taker, 当发生自成交时，撤销taker单
cancel_both,当发生自成交时，同时撤销taker和maker单
cancel both不支持FOK</span></td><td key=5></td></tr><tr key=0-1-10><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> tag</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">订单标签
字母（区分大小写）与数字的组合，可以是纯字母、纯数字，且长度在1-16位之间。</span></td><td key=5></td></tr><tr key=0-1-11><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> source</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">订单来源
13:策略委托单触发后的生成的限价单</span></td><td key=5></td></tr><tr key=0-1-12><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> ccy</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">保证金币种</span></td><td key=5></td></tr><tr key=0-1-13><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> posSide</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">持仓方向
`long` 多仓
`short` 空仓</span></td><td key=5></td></tr><tr key=0-1-14><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> tpTriggerPxType</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">止盈触发价类型</span></td><td key=5><p key=2><span style="font-weight: '700'">枚举: </span><span>last,index,mark</span></p><p key=3><span style="font-weight: '700'">枚举备注: </span><span>last :市场价格:盘内最新成交价格（默认）
index :指数价格
mark :标记价格</span></p><p key=5><span style="font-weight: '700'">mock: </span><span>@pick(["last","index","mark"])</span></p></td></tr><tr key=0-1-15><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> tpTriggerPx</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">止盈触发价，如果填写此参数，必须填写 止盈委托价</span></td><td key=5></td></tr><tr key=0-1-16><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> tpOrdPx</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">止盈委托价，如果填写此参数，必须填写 止盈触发价
委托价格 >= 0, 执行限价止盈
委托价格为-1时, 执行市价止盈</span></td><td key=5></td></tr><tr key=0-1-17><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> slTriggerPx</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">止损触发价，如果填写此参数，必须填写 止损委托价</span></td><td key=5></td></tr><tr key=0-1-18><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> slOrdPx</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">止损委托价，如果填写此参数，必须填写 止损触发价
委托价格 >= 0, 执行限价止盈
委托价格为-1时, 执行市价止盈</span></td><td key=5></td></tr><tr key=0-1-19><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> slTriggerPxType</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">止损触发价类型</span></td><td key=5><p key=2><span style="font-weight: '700'">枚举: </span><span>last,index,mark</span></p><p key=3><span style="font-weight: '700'">枚举备注: </span><span>last :市场价格:盘内最新成交价格（默认）
index :指数价格
mark :标记价格</span></p><p key=5><span style="font-weight: '700'">mock: </span><span>@pick(["last","index","mark"])</span></p></td></tr><tr key=0-1-20><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> ordId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">订单ID</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>123456</span></p></td></tr><tr key=0-1-21><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> tpAlgoClOrdId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">下单附带止盈时，客户自定义的策略订单ID</span></td><td key=5></td></tr><tr key=0-1-22><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> slAlgoClOrdId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">下单附带止损时，客户自定义的策略订单ID</span></td><td key=5></td></tr><tr key=0-1-23><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> lever</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">杠杆倍数</span></td><td key=5></td></tr><tr key=0-1-24><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> orderResponseType</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">订单是否同步返回
FULL：同步返回
RESULT: 异步返回</span></td><td key=5></td></tr><tr key=0-1-25><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> accFillSz</span></td><td key=1><span>string</span></td><td key=2>必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">累计成交数量
对于币币和杠杆，单位为交易货币，如 BTC-USDT, 单位为 BTC；对于市价单，无论tgtCcy是base_ccy，还是quote_ccy，单位均为交易货币；
对于交割、永续以及期权，单位为张。</span></td><td key=5></td></tr><tr key=0-1-26><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> fillPx</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">最新成交价格，如果成交数量为0，该字段为""</span></td><td key=5></td></tr><tr key=0-1-27><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> tradeId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">最新成交ID</span></td><td key=5></td></tr><tr key=0-1-28><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> fillSz</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">最新成交数量
对于币币和杠杆，单位为交易货币，如 BTC-USDT, 单位为 BTC；对于市价单，无论tgtCcy是base_ccy，还是quote_ccy，单位均为交易货币；
对于交割、永续以及期权，单位为张。</span></td><td key=5></td></tr><tr key=0-1-29><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> fillTime</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">最新成交时间(毫秒数)</span></td><td key=5></td></tr><tr key=0-1-30><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> avgPx</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">平均成交价</span></td><td key=5></td></tr><tr key=0-1-31><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> state</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">订单状态
canceled：撤单成功
live：等待成交
partially_filled：部分成交
filled：完全成交
mmp_canceled：做市商保护机制导致的自动撤单</span></td><td key=5></td></tr><tr key=0-1-32><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> feeCcy</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">交易手续费币种</span></td><td key=5></td></tr><tr key=0-1-33><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> fee</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">手续费与返佣
对于币币和杠杆，为订单交易累计的手续费，平台向用户收取的交易手续费，为负数。如： -0.01
对于交割、永续和期权，为订单交易累计的手续费和返佣</span></td><td key=5></td></tr><tr key=0-1-34><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> cancelSource</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">订单取消来源的原因枚举值代码</span></td><td key=5></td></tr><tr key=0-1-35><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> cancelSourceReason</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">订单取消来源的对应具体原因</span></td><td key=5></td></tr><tr key=0-1-36><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> uTime</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">订单状态更新时间，Unix时间戳的毫秒数格式，如：1597026383085</span></td><td key=5></td></tr><tr key=0-1-37><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> cTime</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">订单状态创建时间，Unix时间戳的毫秒数格式，如：1597026383085</span></td><td key=5></td></tr><tr key=0-1-38><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> pnl</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">最新成交收益，适用于有成交的平仓订单。其他情况均为0。</span></td><td key=5></td></tr><tr key=0-1-39><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> baseCcy</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">基础货币</span></td><td key=5></td></tr><tr key=0-1-40><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> quoteCcy</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">计价货币</span></td><td key=5></td></tr><tr key=0-2><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> code</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">错误码</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1</span></p></td></tr><tr key=0-3><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> ts</span></td><td key=1><span>integer</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">系统时间</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1660101471921</span></p></td></tr><tr key=0-4><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> traceId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr>
               </tbody>
              </table>
            
## GET 获取订单信息
<a id=GET 获取订单信息2744> </a>
### 基本信息

**Path：** /openapi/v3/trade/order

**Method：** GET

**接口描述：**
<p></p>

### 请求参数
**Query**

| 参数名称  |  是否必须 | 示例  | 备注  |
| ------------ | ------------ | ------------ | ------------ |
| instId | 是  |   |  产品ID ，如BTC-USD-190927 |
| instType | 否  |   |   |
| ordId | 否  |   |  订单ID ， ordId和clOrdId必须传一个，若传两个，以ordId为主 |
| clOrdId | 否  |   |  用户自定义ID, 如果clOrdId关联了多个订单，只会返回最近的那笔订单 |

### 返回数据

<table>
  <thead class="ant-table-thead">
    <tr>
      <th key=name>名称</th><th key=type>类型</th><th key=required>是否必须</th><th key=default>默认值</th><th key=desc>备注</th><th key=sub>其他信息</th>
    </tr>
  </thead><tbody className="ant-table-tbody"><tr key=0-0><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> msg</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">请求结果描述。请求成功返回成功描述。发生错误返回具体错误描述。</span></td><td key=5></td></tr><tr key=0-1><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> data</span></td><td key=1><span>object</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">数据</span></td><td key=5></td></tr><tr key=0-1-0><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> instType</span></td><td key=1><span>string</span></td><td key=2>必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">产品类型</span></td><td key=5><p key=2><span style="font-weight: '700'">枚举: </span><span>SPOT,SWAP</span></p><p key=3><span style="font-weight: '700'">枚举备注: </span><span>SPOT :现货
SWAP :永续合约</span></p><p key=5><span style="font-weight: '700'">mock: </span><span>@pick(["SPOT","SWAP"])</span></p></td></tr><tr key=0-1-1><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> instId</span></td><td key=1><span>string</span></td><td key=2>必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">产品ID,例如 BTC_USDT_SWAP</span></td><td key=5></td></tr><tr key=0-1-2><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> clOrdId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">客户自定义订单ID
字母（区分大小写）与数字的组合，可以是纯字母、纯数字且长度要在1-32位之间。</span></td><td key=5></td></tr><tr key=0-1-3><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> side</span></td><td key=1><span>string</span></td><td key=2>必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">订单方向
buy：买， sell：卖</span></td><td key=5></td></tr><tr key=0-1-4><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> ordType</span></td><td key=1><span>string</span></td><td key=2>必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">订单类型</span></td><td key=5><p key=2><span style="font-weight: '700'">枚举: </span><span>market,limit,post_only,fok,ioc,cancel,batch_cancel_and_limit,risk_reduce,risk_close,risk_adl</span></p><p key=3><span style="font-weight: '700'">枚举备注: </span><span>market :市价单
limit :限价单
post_only :只做maker单
fok :全部成交或立即取消
ioc :立即成交并取消剩余
cancel :取消单
batch_cancel_and_limit :批量挂单
risk_reduce :强制减仓
risk_close :强制平仓
risk_adl :ADL减仓单</span></p><p key=5><span style="font-weight: '700'">mock: </span><span>@pick(["market","limit","post_only","fok","ioc","cancel","batch_cancel_and_limit","risk_reduce","risk_close","risk_adl"])</span></p></td></tr><tr key=0-1-5><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> sz</span></td><td key=1><span>string</span></td><td key=2>必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">委托数量</span></td><td key=5></td></tr><tr key=0-1-6><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> px</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">委托价格
仅适用于limit、post_only、fok、ioc</span></td><td key=5></td></tr><tr key=0-1-7><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> tgtCcy</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">市价单委托数量sz的单位，仅适用于币币市价订单
base_ccy: 交易货币
quote_ccy：计价货币
买单默认quote_ccy， 卖单默认base_ccy</span></td><td key=5></td></tr><tr key=0-1-8><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> stpId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">自成交保护ID。来自同一个母账户配着同一个ID的订单不能自成交
用户自定义1<=x<=999999999的整数
默认取账户ID,即同一账户（子账户）内不可以自成交</span></td><td key=5></td></tr><tr key=0-1-9><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> stpMode</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">自成交保护模式
no_cancel, 支持自成交
cancel_maker，当发生自成交时，撤销maker单
cancel_taker, 当发生自成交时，撤销taker单
cancel_both,当发生自成交时，同时撤销taker和maker单
cancel both不支持FOK</span></td><td key=5></td></tr><tr key=0-1-10><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> tag</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">订单标签
字母（区分大小写）与数字的组合，可以是纯字母、纯数字，且长度在1-16位之间。</span></td><td key=5></td></tr><tr key=0-1-11><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> source</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">订单来源
13:策略委托单触发后的生成的限价单</span></td><td key=5></td></tr><tr key=0-1-12><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> ccy</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">保证金币种</span></td><td key=5></td></tr><tr key=0-1-13><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> posSide</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">持仓方向
`long` 多仓
`short` 空仓</span></td><td key=5></td></tr><tr key=0-1-14><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> tpTriggerPxType</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">止盈触发价类型</span></td><td key=5><p key=2><span style="font-weight: '700'">枚举: </span><span>last,index,mark</span></p><p key=3><span style="font-weight: '700'">枚举备注: </span><span>last :市场价格:盘内最新成交价格（默认）
index :指数价格
mark :标记价格</span></p><p key=5><span style="font-weight: '700'">mock: </span><span>@pick(["last","index","mark"])</span></p></td></tr><tr key=0-1-15><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> tpTriggerPx</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">止盈触发价，如果填写此参数，必须填写 止盈委托价</span></td><td key=5></td></tr><tr key=0-1-16><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> tpOrdPx</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">止盈委托价，如果填写此参数，必须填写 止盈触发价
委托价格 >= 0, 执行限价止盈
委托价格为-1时, 执行市价止盈</span></td><td key=5></td></tr><tr key=0-1-17><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> slTriggerPx</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">止损触发价，如果填写此参数，必须填写 止损委托价</span></td><td key=5></td></tr><tr key=0-1-18><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> slOrdPx</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">止损委托价，如果填写此参数，必须填写 止损触发价
委托价格 >= 0, 执行限价止盈
委托价格为-1时, 执行市价止盈</span></td><td key=5></td></tr><tr key=0-1-19><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> slTriggerPxType</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">止损触发价类型</span></td><td key=5><p key=2><span style="font-weight: '700'">枚举: </span><span>last,index,mark</span></p><p key=3><span style="font-weight: '700'">枚举备注: </span><span>last :市场价格:盘内最新成交价格（默认）
index :指数价格
mark :标记价格</span></p><p key=5><span style="font-weight: '700'">mock: </span><span>@pick(["last","index","mark"])</span></p></td></tr><tr key=0-1-20><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> ordId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">订单ID</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>123456</span></p></td></tr><tr key=0-1-21><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> tpAlgoClOrdId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">下单附带止盈时，客户自定义的策略订单ID</span></td><td key=5></td></tr><tr key=0-1-22><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> slAlgoClOrdId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">下单附带止损时，客户自定义的策略订单ID</span></td><td key=5></td></tr><tr key=0-1-23><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> lever</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">杠杆倍数</span></td><td key=5></td></tr><tr key=0-1-24><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> orderResponseType</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">订单是否同步返回
FULL：同步返回
RESULT: 异步返回</span></td><td key=5></td></tr><tr key=0-1-25><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> accFillSz</span></td><td key=1><span>string</span></td><td key=2>必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">累计成交数量
对于币币和杠杆，单位为交易货币，如 BTC-USDT, 单位为 BTC；对于市价单，无论tgtCcy是base_ccy，还是quote_ccy，单位均为交易货币；
对于交割、永续以及期权，单位为张。</span></td><td key=5></td></tr><tr key=0-1-26><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> fillPx</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">最新成交价格，如果成交数量为0，该字段为""</span></td><td key=5></td></tr><tr key=0-1-27><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> tradeId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">最新成交ID</span></td><td key=5></td></tr><tr key=0-1-28><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> fillSz</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">最新成交数量
对于币币和杠杆，单位为交易货币，如 BTC-USDT, 单位为 BTC；对于市价单，无论tgtCcy是base_ccy，还是quote_ccy，单位均为交易货币；
对于交割、永续以及期权，单位为张。</span></td><td key=5></td></tr><tr key=0-1-29><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> fillTime</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">最新成交时间(毫秒数)</span></td><td key=5></td></tr><tr key=0-1-30><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> avgPx</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">平均成交价</span></td><td key=5></td></tr><tr key=0-1-31><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> state</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">订单状态
canceled：撤单成功
live：等待成交
partially_filled：部分成交
filled：完全成交
mmp_canceled：做市商保护机制导致的自动撤单</span></td><td key=5></td></tr><tr key=0-1-32><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> feeCcy</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">交易手续费币种</span></td><td key=5></td></tr><tr key=0-1-33><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> fee</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">手续费与返佣
对于币币和杠杆，为订单交易累计的手续费，平台向用户收取的交易手续费，为负数。如： -0.01
对于交割、永续和期权，为订单交易累计的手续费和返佣</span></td><td key=5></td></tr><tr key=0-1-34><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> cancelSource</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">订单取消来源的原因枚举值代码</span></td><td key=5></td></tr><tr key=0-1-35><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> cancelSourceReason</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">订单取消来源的对应具体原因</span></td><td key=5></td></tr><tr key=0-1-36><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> uTime</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">订单状态更新时间，Unix时间戳的毫秒数格式，如：1597026383085</span></td><td key=5></td></tr><tr key=0-1-37><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> cTime</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">订单状态创建时间，Unix时间戳的毫秒数格式，如：1597026383085</span></td><td key=5></td></tr><tr key=0-1-38><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> pnl</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">最新成交收益，适用于有成交的平仓订单。其他情况均为0。</span></td><td key=5></td></tr><tr key=0-1-39><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> baseCcy</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">基础货币</span></td><td key=5></td></tr><tr key=0-1-40><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> quoteCcy</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">计价货币</span></td><td key=5></td></tr><tr key=0-2><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> code</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">错误码</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1</span></p></td></tr><tr key=0-3><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> ts</span></td><td key=1><span>integer</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">系统时间</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1660101471921</span></p></td></tr><tr key=0-4><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> traceId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr>
               </tbody>
              </table>
            
## algoOrdersPending
<a id=algoOrdersPending2744> </a>
### 基本信息

**Path：** /openapi/v3/trade/orders-algo-pending

**Method：** GET

**接口描述：**


### 请求参数
**Query**

| 参数名称  |  是否必须 | 示例  | 备注  |
| ------------ | ------------ | ------------ | ------------ |
| instType | 否  |   |   |
| instId | 否  |   |   |
| ordType | 否  |   |   |
| algoId | 否  |   |   |
| algoClOrdId | 否  |   |   |
| begin | 否  |   |   |
| end | 否  |   |   |
| limit | 否  |   |   |

### 返回数据

<table>
  <thead class="ant-table-thead">
    <tr>
      <th key=name>名称</th><th key=type>类型</th><th key=required>是否必须</th><th key=default>默认值</th><th key=desc>备注</th><th key=sub>其他信息</th>
    </tr>
  </thead><tbody className="ant-table-tbody"><tr key=0-0><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> msg</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">请求结果描述。请求成功返回成功描述。发生错误返回具体错误描述。</span></td><td key=5></td></tr><tr key=0-1><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> data</span></td><td key=1><span>object []</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">数据</span></td><td key=5><p key=3><span style="font-weight: '700'">item 类型: </span><span>object</span></p></td></tr><tr key=0-1-0><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> instId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr><tr key=0-1-1><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> ccy</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr><tr key=0-1-2><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> side</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr><tr key=0-1-3><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> posSide</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr><tr key=0-1-4><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> ordType</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5><p key=2><span style="font-weight: '700'">枚举: </span><span>conditional,oco,trigger</span></p><p key=3><span style="font-weight: '700'">枚举备注: </span><span>conditional :单项止盈止损
oco :双向止盈止损
trigger :计划委托</span></p><p key=5><span style="font-weight: '700'">mock: </span><span>@pick(["conditional","oco","trigger"])</span></p></td></tr><tr key=0-1-5><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> sz</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr><tr key=0-1-6><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> tag</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr><tr key=0-1-7><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> tgtCcy</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr><tr key=0-1-8><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> algoClOrdId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr><tr key=0-1-9><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> tpAlgoClOrdId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr><tr key=0-1-10><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> slAlgoClOrdId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr><tr key=0-1-11><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> closeFraction</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">策略委托触发时，平仓的百分比。1 代表100%
现在系统只支持全部平仓，唯一接受参数为1
仅适用于交割或永续
当posSide = net时，reduceOnly必须为true
仅适用于止盈止损 ordType = conditional 或 oco
仅适用于止盈止损市价订单
不支持组合保证金模式
sz和closeFraction必填且只能填其一</span></td><td key=5></td></tr><tr key=0-1-12><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> tpTriggerPx</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">仅适用于止盈止损 ordType = conditional 或 oco</span></td><td key=5></td></tr><tr key=0-1-13><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> tpTriggerPxType</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">仅适用于止盈止损 ordType = conditional 或 oco</span></td><td key=5><p key=2><span style="font-weight: '700'">枚举: </span><span>last,index,mark</span></p><p key=3><span style="font-weight: '700'">枚举备注: </span><span>last :市场价格:盘内最新成交价格（默认）
index :指数价格
mark :标记价格</span></p><p key=5><span style="font-weight: '700'">mock: </span><span>@pick(["last","index","mark"])</span></p></td></tr><tr key=0-1-14><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> tpOrdPx</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">仅适用于止盈止损 ordType = conditional 或 oco,  -1 代表市价挂单， >0 代表限价挂单挂单价</span></td><td key=5></td></tr><tr key=0-1-15><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> slTriggerPx</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">仅适用于止盈止损 ordType = conditional 或 oco</span></td><td key=5></td></tr><tr key=0-1-16><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> slTriggerPxType</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">仅适用于止盈止损 ordType = conditional 或 oco</span></td><td key=5><p key=2><span style="font-weight: '700'">枚举: </span><span>last,index,mark</span></p><p key=3><span style="font-weight: '700'">枚举备注: </span><span>last :市场价格:盘内最新成交价格（默认）
index :指数价格
mark :标记价格</span></p><p key=5><span style="font-weight: '700'">mock: </span><span>@pick(["last","index","mark"])</span></p></td></tr><tr key=0-1-17><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> slOrdPx</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">仅适用于止盈止损 ordType = conditional 或 oco，-1 代表市价挂单， >0 代表限价挂单挂单价</span></td><td key=5></td></tr><tr key=0-1-18><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> cxlOnClosePos</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">决定用户所下的止盈止损订单是否与该交易产品对应的仓位关联。若关联，仓位被撤销时，该止盈止损订单会被同时撤销；若不关联，仓位被撤销时，该止盈止损订单不受影响。
<p>
有效值：
true：下单与仓位关联的止盈止损订单
false：下单与仓位不关联的止盈止损订单
<p>
默认值为true。若传入true，用户必须同时传入 reduceOnly = true，说明当下单与仓位关联的止盈止损订单时，必须为只减仓。
<p>
适用于单币种保证金模式、跨币种保证金模式。
<p>
仅适用于止盈止损 ordType = conditional 或 oco</span></td><td key=5></td></tr><tr key=0-1-19><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> reduceOnly</span></td><td key=1><span>boolean</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">仅适用于止盈止损 ordType = conditional 或 oco</span></td><td key=5></td></tr><tr key=0-1-20><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> triggerPx</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">仅适用于计划委托 ordType = trigger</span></td><td key=5></td></tr><tr key=0-1-21><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> triggerPxType</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">仅适用于计划委托 ordType = trigger</span></td><td key=5><p key=2><span style="font-weight: '700'">枚举: </span><span>last,index,mark</span></p><p key=3><span style="font-weight: '700'">枚举备注: </span><span>last :市场价格:盘内最新成交价格（默认）
index :指数价格
mark :标记价格</span></p><p key=5><span style="font-weight: '700'">mock: </span><span>@pick(["last","index","mark"])</span></p></td></tr><tr key=0-1-22><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> orderPx</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">仅适用于计划委托 ordType = trigger -1 代表市价挂单， >0 代表限价挂单挂单价</span></td><td key=5></td></tr><tr key=0-1-23><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> px</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">委托价格</span></td><td key=5></td></tr><tr key=0-1-24><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> ordId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr><tr key=0-1-25><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> ordIdList</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr><tr key=0-1-26><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> state</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr><tr key=0-1-27><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> triggerTime</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">private String actualSz;</span></td><td key=5></td></tr><tr key=0-1-28><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> last</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr><tr key=0-1-29><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> failCode</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr><tr key=0-1-30><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> cTime</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr><tr key=0-1-31><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> uTime</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr><tr key=0-2><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> code</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">错误码</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1</span></p></td></tr><tr key=0-3><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> ts</span></td><td key=1><span>integer</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">系统时间</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1660101471921</span></p></td></tr><tr key=0-4><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> traceId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr>
               </tbody>
              </table>
            
## batchCancelAlgoOrders
<a id=batchCancelAlgoOrders2744> </a>
### 基本信息

**Path：** /openapi/v3/trade/cancel-batch-algos

**Method：** POST

**接口描述：**


### 请求参数
**Headers**

| 参数名称  | 参数值  |  是否必须 | 示例  | 备注  |
| ------------ | ------------ | ------------ | ------------ | ------------ |
| Content-Type  |  application/json | 是  |  application/json |   |
**Body**

<table>
  <thead class="ant-table-thead">
    <tr>
      <th key=name>名称</th><th key=type>类型</th><th key=required>是否必须</th><th key=default>默认值</th><th key=desc>备注</th><th key=sub>其他信息</th>
    </tr>
  </thead><tbody className="ant-table-tbody"><tr key=0><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> </span></td><td key=1><span>object []</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5><p key=3><span style="font-weight: '700'">item 类型: </span><span>object</span></p></td></tr><tr key=0-0><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> instId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">产品ID,例如 BTC_USDT_SWAP</span></td><td key=5></td></tr><tr key=0-1><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> algoId</span></td><td key=1><span>string</span></td><td key=2>必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">策略委托单ID</span></td><td key=5></td></tr>
               </tbody>
              </table>
            
### 返回数据

<table>
  <thead class="ant-table-thead">
    <tr>
      <th key=name>名称</th><th key=type>类型</th><th key=required>是否必须</th><th key=default>默认值</th><th key=desc>备注</th><th key=sub>其他信息</th>
    </tr>
  </thead><tbody className="ant-table-tbody"><tr key=0-0><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> msg</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">请求结果描述。请求成功返回成功描述。发生错误返回具体错误描述。</span></td><td key=5></td></tr><tr key=0-1><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> data</span></td><td key=1><span>object []</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">数据</span></td><td key=5><p key=3><span style="font-weight: '700'">item 类型: </span><span>object</span></p></td></tr><tr key=0-1-0><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> algoId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">订单ID</span></td><td key=5></td></tr><tr key=0-1-1><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> algoClOrdId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">客户自定义订单ID</span></td><td key=5></td></tr><tr key=0-1-2><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> sCode</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">此事件执行结果的code，0代表成功</span></td><td key=5></td></tr><tr key=0-1-3><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> sMsg</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">此事件执行失败或成功时的msg</span></td><td key=5></td></tr><tr key=0-1-4><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> algoId2</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">订单ID</span></td><td key=5></td></tr><tr key=0-1-5><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> algoClOrdId2</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">客户自定义订单ID</span></td><td key=5></td></tr><tr key=0-2><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> code</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">错误码</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1</span></p></td></tr><tr key=0-3><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> ts</span></td><td key=1><span>integer</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">系统时间</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1660101471921</span></p></td></tr><tr key=0-4><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> traceId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr>
               </tbody>
              </table>
            
## placeAlgoOrder
<a id=placeAlgoOrder2744> </a>
### 基本信息

**Path：** /openapi/v3/trade/create-order-algo

**Method：** POST

**接口描述：**


### 请求参数
**Headers**

| 参数名称  | 参数值  |  是否必须 | 示例  | 备注  |
| ------------ | ------------ | ------------ | ------------ | ------------ |
| Content-Type  |  application/json | 是  |  application/json |   |
**Body**

<table>
  <thead class="ant-table-thead">
    <tr>
      <th key=name>名称</th><th key=type>类型</th><th key=required>是否必须</th><th key=default>默认值</th><th key=desc>备注</th><th key=sub>其他信息</th>
    </tr>
  </thead><tbody className="ant-table-tbody"><tr key=0-0><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> instId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr><tr key=0-1><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> ccy</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr><tr key=0-2><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> side</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr><tr key=0-3><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> posSide</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr><tr key=0-4><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> ordType</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5><p key=2><span style="font-weight: '700'">枚举: </span><span>conditional,oco,trigger</span></p><p key=3><span style="font-weight: '700'">枚举备注: </span><span>conditional :单项止盈止损
oco :双向止盈止损
trigger :计划委托</span></p><p key=5><span style="font-weight: '700'">mock: </span><span>@pick(["conditional","oco","trigger"])</span></p></td></tr><tr key=0-5><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> sz</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr><tr key=0-6><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> tag</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr><tr key=0-7><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> tgtCcy</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr><tr key=0-8><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> algoClOrdId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr><tr key=0-9><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> tpAlgoClOrdId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr><tr key=0-10><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> slAlgoClOrdId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr><tr key=0-11><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> closeFraction</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">策略委托触发时，平仓的百分比。1 代表100%
现在系统只支持全部平仓，唯一接受参数为1
仅适用于交割或永续
当posSide = net时，reduceOnly必须为true
仅适用于止盈止损 ordType = conditional 或 oco
仅适用于止盈止损市价订单
不支持组合保证金模式
sz和closeFraction必填且只能填其一</span></td><td key=5></td></tr><tr key=0-12><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> tpTriggerPx</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">仅适用于止盈止损 ordType = conditional 或 oco</span></td><td key=5></td></tr><tr key=0-13><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> tpTriggerPxType</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">仅适用于止盈止损 ordType = conditional 或 oco</span></td><td key=5><p key=2><span style="font-weight: '700'">枚举: </span><span>last,index,mark</span></p><p key=3><span style="font-weight: '700'">枚举备注: </span><span>last :市场价格:盘内最新成交价格（默认）
index :指数价格
mark :标记价格</span></p><p key=5><span style="font-weight: '700'">mock: </span><span>@pick(["last","index","mark"])</span></p></td></tr><tr key=0-14><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> tpOrdPx</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">仅适用于止盈止损 ordType = conditional 或 oco,  -1 代表市价挂单， >0 代表限价挂单挂单价</span></td><td key=5></td></tr><tr key=0-15><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> slTriggerPx</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">仅适用于止盈止损 ordType = conditional 或 oco</span></td><td key=5></td></tr><tr key=0-16><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> slTriggerPxType</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">仅适用于止盈止损 ordType = conditional 或 oco</span></td><td key=5><p key=2><span style="font-weight: '700'">枚举: </span><span>last,index,mark</span></p><p key=3><span style="font-weight: '700'">枚举备注: </span><span>last :市场价格:盘内最新成交价格（默认）
index :指数价格
mark :标记价格</span></p><p key=5><span style="font-weight: '700'">mock: </span><span>@pick(["last","index","mark"])</span></p></td></tr><tr key=0-17><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> slOrdPx</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">仅适用于止盈止损 ordType = conditional 或 oco，-1 代表市价挂单， >0 代表限价挂单挂单价</span></td><td key=5></td></tr><tr key=0-18><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> cxlOnClosePos</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">决定用户所下的止盈止损订单是否与该交易产品对应的仓位关联。若关联，仓位被撤销时，该止盈止损订单会被同时撤销；若不关联，仓位被撤销时，该止盈止损订单不受影响。
<p>
有效值：
true：下单与仓位关联的止盈止损订单
false：下单与仓位不关联的止盈止损订单
<p>
默认值为true。若传入true，用户必须同时传入 reduceOnly = true，说明当下单与仓位关联的止盈止损订单时，必须为只减仓。
<p>
适用于单币种保证金模式、跨币种保证金模式。
<p>
仅适用于止盈止损 ordType = conditional 或 oco</span></td><td key=5></td></tr><tr key=0-19><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> reduceOnly</span></td><td key=1><span>boolean</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">仅适用于止盈止损 ordType = conditional 或 oco</span></td><td key=5></td></tr><tr key=0-20><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> triggerPx</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">仅适用于计划委托 ordType = trigger</span></td><td key=5></td></tr><tr key=0-21><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> triggerPxType</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">仅适用于计划委托 ordType = trigger</span></td><td key=5><p key=2><span style="font-weight: '700'">枚举: </span><span>last,index,mark</span></p><p key=3><span style="font-weight: '700'">枚举备注: </span><span>last :市场价格:盘内最新成交价格（默认）
index :指数价格
mark :标记价格</span></p><p key=5><span style="font-weight: '700'">mock: </span><span>@pick(["last","index","mark"])</span></p></td></tr><tr key=0-22><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> orderPx</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">仅适用于计划委托 ordType = trigger -1 代表市价挂单， >0 代表限价挂单挂单价</span></td><td key=5></td></tr><tr key=0-23><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> px</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">委托价格</span></td><td key=5></td></tr>
               </tbody>
              </table>
            
### 返回数据

<table>
  <thead class="ant-table-thead">
    <tr>
      <th key=name>名称</th><th key=type>类型</th><th key=required>是否必须</th><th key=default>默认值</th><th key=desc>备注</th><th key=sub>其他信息</th>
    </tr>
  </thead><tbody className="ant-table-tbody"><tr key=0-0><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> msg</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">请求结果描述。请求成功返回成功描述。发生错误返回具体错误描述。</span></td><td key=5></td></tr><tr key=0-1><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> data</span></td><td key=1><span>object</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">数据</span></td><td key=5></td></tr><tr key=0-1-0><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> algoId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">订单ID</span></td><td key=5></td></tr><tr key=0-1-1><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> algoClOrdId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">客户自定义订单ID</span></td><td key=5></td></tr><tr key=0-1-2><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> sCode</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">此事件执行结果的code，0代表成功</span></td><td key=5></td></tr><tr key=0-1-3><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> sMsg</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">此事件执行失败或成功时的msg</span></td><td key=5></td></tr><tr key=0-1-4><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> algoId2</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">订单ID</span></td><td key=5></td></tr><tr key=0-1-5><td key=0><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> algoClOrdId2</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">客户自定义订单ID</span></td><td key=5></td></tr><tr key=0-2><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> code</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">错误码</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1</span></p></td></tr><tr key=0-3><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> ts</span></td><td key=1><span>integer</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap">系统时间</span></td><td key=5><p key=5><span style="font-weight: '700'">mock: </span><span>1660101471921</span></p></td></tr><tr key=0-4><td key=0><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> traceId</span></td><td key=1><span>string</span></td><td key=2>非必须</td><td key=3></td><td key=4><span style="white-space: pre-wrap"></span></td><td key=5></td></tr>
               </tbody>
              </table>
            
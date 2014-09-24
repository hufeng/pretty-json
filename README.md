pretty-json
===========

简单地包装python -mjson.tool格式化json输出

使用方式：

<code><pre>
    λ: sh pjson '{"id:1, "name":"python"}' #注意单引号包裹,适合少量数据
    {
    &nbsp;&nbsp;&nbsp;&nbsp;"id": 1,
    &nbsp;&nbsp;&nbsp;&nbsp;"name": "python"
    }
</pre></code>
<code><pre>
    λ: sh pjson #回车,适合大数据量
    {"id":1, "name": "python"}
    {
    &nbsp;&nbsp;&nbsp;&nbsp;"id": 1,
    &nbsp;&nbsp;&nbsp;&nbsp;"name": "python"
    } 
</pre></code>

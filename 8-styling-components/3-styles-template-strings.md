# 样式应该放在模板字符串中

风格的jsx作为一个babel插件。 它将解析所有的CSS并在构建过程中应用它。 （随着我们的风格得到应用，没有任何额外开销时间）

它还支持在styled-jsx中具有约束。 将来，您将能够使用styled-jsx内的任何动态变量。 这就是为什么CSS需要在模板字符串里面。 （``{` `}``）
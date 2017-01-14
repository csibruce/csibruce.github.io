---
layout: post
title: 블로그를 시작하며..
category: sample
tag: [jekyll, blog]
---

앞으로 [github pages](https://pages.github.com/)를 이용해 블로그를 운영해볼생각이다.
라즈베리파이, 아두이노, node, react, javascript에 관련된 내용들이 포스팅 될 예정이다.

### 테마설정 완료.
### Disqus 설정 완료.

### 코드 잘 써지나 테스트
~~~
import React from 'react';
import { View, Text, Image } from 'react-native';

import I18n from '@helpers/i18n';

import styles from './styles';

type Props = {
  version: String,
}

const TestContainer = ({ version }: Props) => (
  <View style={styles.container}>
    <View style={styles.image}>
      <Image source={} />
    </View>
    <Text style={styles.versionText}>
      {}
    </Text>
  </View>
);

export default TestContainer;

~~~
{: .language-js}

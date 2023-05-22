
# 基本知識の学習（復習）
## 1. TDD環境の構築
### 1.1 GoogleTest導入
### 1.2 GoogleTestの使い方
#include "pch.h" <br>
TEST(TestCaseName, TestName){ <br>
//Arrange <br>
//Act <br>
//Assert <br>
} <br>

### Assertの内容
・定義：gtest/gtest.h <br>
・数値の比較 <br>
  ASSERT_EQ(a, b) // a==b <br>
  ASSERT_NE(a, b) // a!=b <br><br>
  ASSERT_LE(a, b) // a<=b <br>
  ASSERT_GE(a, b) // a>=b <br><br>
  ASSERT_LT(a, b) // a<b <br>
  ASSERT_GT(a, b) // a>b <br>
  
・他の数値の比較 <br> 
  ASSERT_FLOAT_EQ <br>
  ASSERT_DOUBLE_EQ <br>
  
・文字列の比較 <br>
  ASSERT_STREQ(s1, s2) // s1 == s2 <br>
  ASSERT_STRNE(s1, s2) // s1 != s2 <br><br>
  ASSERT_STRCASEEQ(s1, s2)  // s1 == s2, ignoring case <br>
  ASSERT_STRCASENE(s1, s2)  // s1 != s2, ignoring case <br>
  
・例外処理 <br> 
  ASSERT_THROW(statement,exception)
  ASSERT_ANY_THROW(statement)
  ASSERT_NO_THROW(statement)

## 3. namespace


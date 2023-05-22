
# 基本知識の学習（復習）
## 1. TDD環境の構築
### 1.1 GoogleTest導入
### 1.2 GoogleTestの使い方
TEST(TestCaseName, TestName){ <br>
//Arrange <br>
//Act <br>
//Assert <br>
}

### Assertの内容
・定義：gtest/gtest.h <br>
・数値の比較 <br>
  ASSERT_EQ(a, b) // a==b <br>
  ASSERT_NE(a, b) // a!=b <br><br>
  ASSERT_LE(a, b) // a<=b <br>
  ASSERT_GE(a, b) // a>=b <br><br>
  ASSERT_LT(a, b) // a<b <br>
  ASSERT_GT(a, b) // a>b <br>

## 3. namespace


No, a `constexpr` function may only contains statements that generate no actions at run time, but the member method `size()` must be called at run time, thus the function can not be a `constexpr` function.

<!---
A function like below can be `constexpr` function:

    constexpr bool isSameStr(const std::string &s1, const std::string &s2) {
      return &s1 == &s2;
    }

--->


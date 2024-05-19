![[Pasted image 20240518182053.png]]

---
![[Pasted image 20240518182158.png]]

---
![[Pasted image 20240518182334.png]]
![[Pasted image 20240518182345.png]]
![[Pasted image 20240518182429.png]]
![[Pasted image 20240518182444.png]]
![[Pasted image 20240518182458.png]]

```js
const tweetsService = require("./tweetsService");
const tweetsRepository = require("../repositories/tweetsRepository");

jest.mock("../repositories/tweetsRepository", () => ({
  getTweets: jest.fn(() => ["tweet1", "tweet2"]),
}));

describe("[ services / tweetsService ]", () => {
  describe("#getTweets", () => {
    it("should get all tweets", async () => {
      // Arrange
      const expected = ["tweet1", "tweet2"];

      // Act
      const result = await tweetsService.getTweets();

      // Assert
      expect(result).toEqual(expected);

      // Another Assert
      expect(tweetsRepository.getTweets).toHaveBeenCalled();
    });
  });
});
```
![[Pasted image 20240518182513.png]]
![[Pasted image 20240518182524.png]]

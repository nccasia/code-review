<img src="https://avatars.githubusercontent.com/u/57796807?s=200&v=4" width="30" />

Official code review guideline of NCCPLUS

[Github](https://github.com/nccasia/code-review)

## Key factors

- [Review PR and commits](#review-pr-and-commits)
- [Review functional requirements](#review-functional-requirements)
- [Review non-functional requirements](#review-non-functional-requirements)
- [Review testing & testability](#review-testing-testability)

## Review PR and commits

- [ ] Check branch [#1](#)
- [ ] Check account [#1](#)
- [ ] Check description [#1](#)
- [ ] Check commit message [#1](#)
- [ ] Check files and change scopes [#1](#)
- [ ] Check sensitive data (private key/password) [#1](#)

## Review functional requirements

- [ ] Đảm bảo PR cover đúng và đủ yêu cầu của ticket [#1](#)
- [ ] Có ảnh hưởng chức năng cũ hay ko 

## Review non-functional requirements
- [ ] Code readability [#1](#)
- [ ] Code có dễ hiểu ko, có phần nào gây khó hiểu ko và vì sao [#1](#)
- [ ] Code ở trong đúng structure của project chưa [#1](#)
- [ ] Tên biến, tên hàm đã đúng naming convention chưa [#1](#)
- [ ] Đã loại bỏ hết hard coding/magic number chưa implementation [#1](#)
- [ ] Có giải pháp nào đơn giản hơn không  [#1](#)
- [ ] Loại bỏ functions/methods/variables/packages/libs không sử dụng  [#1](#)
- [ ] Event listeners removed at destruction  [#1](#)
- [ ] Tránh quá nhiều if/else block  [#1](#)
- [ ] Reusability  [#1](#)
- [ ] Check duplicate code [#1](#)  [#1](#)
- [ ] Cân nhắc sử dụng service chung/component chung  [#1](#)
- [ ] Reliability [#](#1)
- [ ] Message thân thiện với user ko [#1](#)
- [ ] Có nên thêm/loại bớt logging ko [#1](#)

## Review testing & testability 
- [ ] Code có thể được test ko [#1](#)
- [ ] Có unit/integration/system test không [#1](#)
- [ ] Testcase hiện có cover được thay đổi không [#1](#)
- [ ] Có cần bổ sung thêm test case không [#1](#)
- [ ] Có ảnh hưởng test cases cũ hay không [#1](#)

Copyright [nccplus](https://ncc.asia) all rights reserved

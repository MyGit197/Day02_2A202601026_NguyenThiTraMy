# Individual Reflection

Trong lab này, nhóm đã chọn bài toán: tìm đúng slide bài giảng trên E3 và hỗ trợ giảng viên/TA trả lời các thắc mắc lặp lại liên quan đến deadline, format và nội dung môn học. Qua quá trình làm việc, tôi nhận ra rằng việc chọn một problem tốt không nằm ở việc “AI có thể làm gì”, mà nằm ở việc hiểu rõ người bị ảnh hưởng, workflow hiện tại và điểm nghẽn thật sự.

## Đóng góp của tôi trong nhóm

| Hoạt động | Tôi đã làm gì? | Kết quả |
|---|---|---|
| Scan cá nhân | Đưa ra các candidate problem từ trải nghiệm và quan sát cá nhân, trong đó có các vấn đề liên quan đến tìm thông tin rải rác và tổng hợp thông tin từ nhiều nguồn | Nhóm có thêm nhiều góc nhìn để hội tụ về một bài toán có pain thật |
| Pitch | Trình bày ý tưởng về việc “tìm đúng thông tin nhanh hơn” và làm rõ rằng pain không chỉ là “không tìm thấy tài liệu”, mà còn là phải hỏi lại và chờ trả lời | Ý tưởng của tôi giúp nhóm nhìn thấy mối liên hệ giữa việc tìm slide và việc trả lời câu hỏi lặp lại |
| Challenge | Đặt câu hỏi về phạm vi của bài toán: liệu đây có quá rộng không, liệu AI có thể giải quyết toàn bộ vấn đề hay chỉ một phần cụ thể? | Nhóm thu hẹp scope về một workflow rõ ràng: sinh viên tìm thông tin -> hỏi -> GV/TA tìm lại nguồn -> soạn câu trả lời |
| Workflow | Giúp nhóm làm rõ bước hiện tại và bước tương lai, đặc biệt là điểm nghẽn ở việc tìm lại nguồn chính thức và soạn câu trả lời | Workflow trước/sau trở nên dễ hiểu và có thể dùng để so sánh Rule / Workflow / Agent |
| Research | Theo dõi các giải pháp như FAQ, chatbot từ khóa, và RAG bot để thấy đâu là cách phù hợp nhất cho bài toán nhóm | Nhóm hiểu rằng giải pháp phù hợp là workflow có human review, không phải agent tự trả lời toàn bộ |
| Quyết định | Tham gia phản biện để chọn giữa các candidate và cuối cùng đồng thuận với bài toán E3 + hỗ trợ GV/TA | Nhóm có thể đi sâu vào problem statement và boundary rõ ràng hơn |

## Bảng dùng AI trong reflection

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai/hời hợt ở đâu? | Tôi sửa gì |
|---|---|---|---|---|
| Scan | Gợi ý thêm các vấn đề liên quan đến tìm thông tin, hỏi đáp và workflow lặp lại | Giúp mình mở rộng góc nhìn và nhìn thấy các pain có thể lặp lại | Một số ý tưởng quá rộng hoặc không có bằng chứng thực tế | Tôi bỏ những ý quá tổng quát và chỉ giữ lại những vấn đề có workflow rõ |
| Workflow | Nhờ AI giúp cấu trúc workflow trước/sau và trình bày mỗi bước rõ hơn | Giúp mình chuyển tư duy thô thành sơ đồ logic dễ đọc | AI có xu hướng gộp nhiều bước vào nhau, làm mờ bottleneck thật sự | Tôi tách lại các bước để bottleneck nằm ở việc tìm nguồn và soạn câu trả lời |
| Research | Tìm hiểu các mô hình FAQ, chatbot và RAG bot | Giúp mình biết có những pattern giải quyết vấn đề tương tự trên thị trường | Một số nguồn không có tính ứng dụng trực tiếp cho ngữ cảnh học tập này | Tôi chỉ giữ lại các pattern có giá trị, rồi đối chiếu với dữ kiện của nhóm |
| Problem Statement | Dùng AI để phản biện về tính rõ ràng của actor, workflow, metric và boundary | Giúp mình kiểm tra nếu câu trình bày còn mơ hồ | AI dễ đề xuất giải pháp quá lớn hoặc quá “agentic” | Tôi và nhóm hạ về workflow có review của GV/TA, không chọn giải pháp agent quá sớm |

## Bài học của tôi

Một bài học lớn nhất mà tôi rút ra là: không nên bắt đầu từ AI trước. Nếu chưa hiểu rõ actor, workflow và bottleneck, thì dù dùng công cụ mạnh đến đâu vẫn khó tạo ra một giải pháp đúng. Trong bài toán này, pain thật không chỉ là “sinh viên không tìm được slide”, mà còn là “cả sinh viên và GV/TA đều phải mất công vì thông tin bị phân mảnh và nhiều câu hỏi lặp lại”.

Tôi cũng học được rằng việc vẽ workflow là bước rất quan trọng. Khi workflow được vẽ rõ, ta mới thấy bước nào thực sự gây lãng phí thời gian, và từ đó mới biết Rule, Workflow hay Agent phù hợp ở đâu. Trong trường hợp này, giải pháp Workflow hợp lý hơn vì nó giữ được human review, giảm rủi ro hallucination và vẫn giúp tiết kiệm thời gian cho cả hai phía.

Ngoài ra, tôi thấy mình học được cách lắng nghe nhiều góc nhìn hơn. Một vấn đề có thể xuất phát từ một người, nhưng khi nhóm cùng nhìn lại thì ta thấy nó ảnh hưởng đến nhiều actor khác nhau. Điều này giúp tôi hiểu rằng giải pháp tốt không chỉ giải quyết pain của người đề xuất, mà còn phải có giá trị thực tế cho những người liên quan.

## Nếu làm lại, tôi sẽ đổi gì

Nếu làm lại lần sau, tôi sẽ dành nhiều thời gian hơn cho việc kiểm chứng pain trước khi quyết định chọn problem. Tôi muốn hỏi thêm nhiều người thật đang chịu tác động trực tiếp, chẳng hạn sinh viên và GV/TA, để hiểu rõ hơn họ mất thời gian ở đâu, họ cần điều gì ở giải pháp cuối cùng, và đâu là điểm cần giữ lại để không làm giải pháp quá rộng. Tôi cũng sẽ định nghĩa metric rõ hơn từ đầu, vì metrics giúp mình biết liệu một giải pháp có thực sự cải thiện workflow hay không, thay vì chỉ dừng ở một ý tưởng “có vẻ hữu ích”.

Tóm lại, lab này giúp tôi hiểu sâu hơn về cách làm việc problem-first: bắt đầu từ pain thật, làm rõ workflow, chọn giải pháp phù hợp và dùng AI ở đúng chỗ, thay vì dùng AI để “giải quyết mọi thứ”.

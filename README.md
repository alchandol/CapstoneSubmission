This repository contains all files leading up to the Capstone project.
- WebScraper : Data analysis and exploration and wrangling performed here
- NER : Initial project prototyping where I attempted to build a custom Named Entity Recognition tool to identify required keywords from input.
        This was the foundation to what the project is now but ultimately, this was scrapped as decision was made to move with LLM.
- LLM : This contains work done for utilizing LLM to achieve feedback text analysis.

The project is a feedback analyzer that produces an overall rating and workplace appropriateness score for the feedback text provided by the user through GPT 3.5.  

To check the deployed app, go here: https://feedbackanalysis-84qrtyvzvbqvy2xehhqbrc.streamlit.app/



Realistic Test Cases

In some cases, there are two sections: Appreciative Feedback (did well), Constructive Feedback (could do better)

T1
Feedback Text: James has been absolutely stellar on Series A financing. The client is extremely frustrating/demanding but James has run the show, basically by himself, and engendered the trust of the partner, myself, and the client. He has also managed to do it with an extraordinarily positive attitude. I am extremely appreciative.

Appropriateness Score: 10. This feedback is appropriate for a professional workplace setting. It does not contain any inappropriate language or derogatory remarks.

Feedback Score: 10. The feedback is highly positive and acknowledges James' stellar performance in handling Series A financing. The reviewer recognizes James' ability to handle a demanding client and run the show effectively. The feedback also highlights James' positive attitude throughout the process, which is appreciated by the reviewer. The overall tone is very positive and appreciative.


T2
Feedback Text: James is an excellent supervisor who provides clear direction and timelines, valuable context (I was recently added to this client so it is helpful to understand the folks at the company we are interacting with), and good precedent for drafting novel docs, in addition to him being an excellent lawyer.

Appropriateness Score: 10. This feedback is appropriate for a professional workplace setting. It does not contain any inappropriate language or derogatory remarks.

Feedback Score: 9. The feedback is highly positive and acknowledges James as an excellent supervisor. The reviewer appreciates James' ability to provide clear direction, timelines, and valuable context for the client they are interacting with. The feedback also recognizes James' expertise in drafting novel documents and overall excellence as a lawyer. The tone is positive and appreciative, with a focus on James' valuable contributions to the team.


T3
Appreciative Feedback: I have been extremely impressed by James's work product and attention to detail. He is very proactive and has consistently taken the initiative to answer client questions in a timely manner when they come in. James "runs" with his assignments and takes complete ownership of his work. He is an excellent junior associate with a bright future!

Appropriateness Score: 10. This feedback is appropriate for a professional workplace setting. It does not contain any inappropriate language or derogatory remarks.

Feedback Score: 10. The feedback is highly positive and expresses admiration for James' work product, attention to detail, and proactive nature. The reviewer appreciates James' promptness in addressing client questions and notes his ability to take ownership of his work. The feedback also recognizes James as an excellent junior associate with a bright future. The tone is highly positive and showcases a high level of satisfaction and confidence in James' abilities.

Constructive Feedback: I don't have much constructive feedback to report, other than my recommendation to continue getting reps (on both the company and investor side). James has great instincts, which will only get better as he continues to hone his substantive knowledge of legal issues. As a junior associate, he should continue to ask questions of the mid and senior associates on his team to understand the "why" behind our recommendations to the client. I have no doubt that as James becomes more experienced, he will be running client relationships as the lead associate with a partner.

Appropriateness Score: 10. This feedback is appropriate for a professional workplace setting. It does not contain any inappropriate language or derogatory remarks.

Feedback Score: 9. The feedback is positive and provides constructive suggestions for James' professional growth. The reviewer acknowledges James' great instincts and recommends that he continue gaining experience and knowledge in legal issues. The feedback also encourages James to ask questions to understand the reasoning behind recommendations. The reviewer expresses confidence in James' future growth and potential as a lead associate. The tone is positive and supportive, with a focus on James' development and future potential.




T4
Appreciative Feedback: You did a great job getting this deal from zero to closed. I really appreciate your feedback and comments, and I think you have developed a great understanding of what is important and what isn't. Your markups were very helpful in speeding along my review, and I think you did a great job negotiating the opposite side.

Appropriateness Score: 10. This feedback is appropriate for a professional workplace setting. It does not contain any inappropriate language or derogatory remarks.

Feedback Score: 10. The feedback is highly positive and acknowledges the recipient's great job in successfully closing the deal. The reviewer expresses appreciation for the recipient's feedback, comments, and understanding of important aspects. The feedback also recognizes the recipient's helpful markups and negotiation skills. The tone is positive and appreciative, highlighting the recipient's contributions and effectiveness in the deal process.

Constructive Feedback: My only constructive feedback is related to deal process efficiency. As we discussed, it's often valuable to get specialist feedback in the early stages of a markup, but I think once you're at short strokes in a financing, it's reasonable (from a cost-efficiency perspective and a deal velocity perspective) to not send minor changes back to the specialists.

Appropriateness Score: 10. This feedback is appropriate for a professional workplace setting. It does not contain any inappropriate language or derogatory remarks.

Feedback Score: 8. The feedback provides constructive feedback regarding deal process efficiency. The reviewer suggests that specialist feedback is valuable in the early stages of a markup, but once the financing is at the final stages, it may not be necessary to send minor changes back to the specialists for efficiency and speed purposes. The tone is constructive and focuses on improving the deal process.
Notice the decrease in Feedback Score as the feedback does outline some areas to improve on.  This is great.

T5
Appreciative Feedback: James tries hard and is responsive.

Appropriateness Score: 10. This feedback is appropriate for a professional workplace setting. It does not contain any inappropriate language or derogatory remarks.

Feedback Score: 7. The feedback acknowledges James' effort and responsiveness. While the feedback is positive, it is relatively neutral and does not provide specific details or examples to highlight James' strengths or areas of improvement. The tone is appreciative but lacks specific enthusiasm or excitement.

Constructive Feedback: James does not understand the substantive issues that have arisen during the transaction and is therefore unable to effectively run the transaction as the senior associate on the matter.
James does not take notes during conversations or does not correctly understand what is discussed in team conversations and does not follow up with questions about items that he does not understand.
James does not succinctly and clearly identify issues or provide clear recommendations to clients regarding transaction matters.

Appropriateness Score: 10. This feedback is appropriate for a professional workplace setting. It does not contain any inappropriate language or derogatory remarks.

Feedback Score: 4. The feedback highlights several areas of concern regarding James' understanding of substantive issues, note-taking skills, and ability to provide clear recommendations to clients. The tone is critical and suggests that James is not effectively running the transaction as a senior associate. The feedback points out specific areas of improvement but does not provide any positive feedback or recognition of James' strengths.

Although professionally written, the feedback contains lots of areas to improve for James.  

T6
Appreciative Feedback: Generally your work product is strong when you deliver.

Appropriateness Score: 10. This feedback is appropriate for a professional workplace setting. It does not contain any inappropriate language or derogatory remarks.

Feedback Score: 9. The feedback acknowledges that the recipient's work product is strong when delivered. While the feedback is generally positive, it suggests that there may be room for improvement in terms of consistency or timeliness in delivering work. The tone is supportive and recognizes the recipient's strengths while also highlighting an area for potential growth.

Constructive Feedback: Time entries can be a bit heavy at times. You should be mindful of this, especially when companies are looking to cut their spending. Figuring out how to streamline your work before getting started on it could help you with this. Sometimes you are in the background and need to be pushed to work on things. I need you to get to a point where you are not waiting for the senior associate/partner to tell you what to do or what to move forward.

Appropriateness Score: 10. This feedback is appropriate for a professional workplace setting. It does not contain any inappropriate language or derogatory remarks.

Feedback Score: 6. The feedback addresses the issue of heavy time entries and suggests being mindful of it, especially in times when companies are looking to cut spending. It also suggests streamlining work processes to improve efficiency. The feedback further highlights the need for the recipient to take more initiative and not rely solely on instructions from senior associates or partners. The tone is constructive but also points out areas of improvement.

Findings
FS ranges about 4~6 score for neutral and goes high or low depending on the strength and emotion behind the feedback.
Because AS looks for appropriateness, generally it’s producing a high rating. This makes sense because if the feedback is workplace appropriate, it should get a higher rating.  Usually 9s and 10s, 8 or below may warrant a second look.  5 or below requires editing.

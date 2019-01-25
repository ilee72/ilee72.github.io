---
layout: essay
type: essay
title: There are no such things as dumb questions
date: 2019-01-24
labels:
  - Technical Essay
  - Javascript
  - Software Engineering
---

## Introduction 
Everyone is always busy with their lives and problems; and making time for a person is one of the greatest gifts a person can give. 
So, it is very essential for anyone asking for someones' time to be thoughtful and considerate for the time and energy spent when someone decides to help a person.
The best way to show such gratitude is to put thought and effort into a problem before asking a question. This means to maybe research or try to solve this problem before giving up to asking questions.
Then you should give as much essential information and context to the question so that those that wish to help do not have to do extra work that could have been done by the one asking the question.
This allows for those that answer questions to add more time and thought to answering the question and giving guidance.

## What a question should contain

Besides the obvious manner of having grammar and appropriate words, the usage of other technical techniques to ensure a proper resposne to a question
are necessary. Judging from all questions that have many responses that were timely and helpful, I saw three things that made this possible.
First, the title of the forum question was concise and summarized the issue that the person was asking for. This would usually be a title that I saw like, "Set padding for UITextField with UITextBorderStyleNone" or "Disable redirect for specific requests with the same client using HTTPClient." From what I see from these titles, these show a way to direct the object/topic of the question and the direction of the question. This makes it easier for others to understand what you are experiencing. 

Second, I saw that these questions provided context to their problem, such as what they were doing or what they were trying to accomplish. In this way, the audience already knows your goals and can create their answers to tailor very closely to the goals of the person. Also, context such as code, background information, or equipment provides additional information that can show how you reached the issue is very helpful to those willing to help. It prevents them from having to make assumptions on certain essential elements of the problem.

Third, I saw that the questions were very specific and technical compared to others. The questions provided certain jargon and specificity that only those familiar in the field could understand the problem. This way, the question asks narrows down on individuals who are familiar with the subject rather than those who are new to it or have never heard of it. Technical jargon also allows for very specific issues which allows for those helping to narrow down their efforts to help solve the issue. 

There were not as many bad questions. The majority of questions were specific, however, there were some sub-par questions that were of poor grammar and were vague and uninteresting. They asked very basic questions that could be searched up on the internet. These questions were with very few views and even fewer answers.

## Interest in questions 
I saw interest in the questions as a great way to see if your question was great or poor. The amount of views and answers were only a implication of the type of question you had. It showed the amount of interest that the question generated and was a great indicator of a great question. Within these responses to the question, many showed enthusiasm in the challenge of the problem and loved to explain and show the corrections or solutions to such questions. Within these responses, others would ask more questions or provide alternate solutions and it would eventually snowball into other topics. When the amount of alternate solutions and the asking of more questions occurs, I saw that the questions that created more interest in depth of a topic were the greatest.

## What I thought was a Great Question
```
https://stackoverflow.com/questions/51972474/override-bash-completion-for-git-clone

The author of this question provides code for a bash completion. Due to my limited technical knowledge, I did not understand as much as I should have. This question shows a very specific amount of technical jargon that would attract those within this subject.

The author is working on a default completion for a git clone that would give tab completion for --* options.
The author asks of making a custom clone tab completion work for the model as well as the default completion continuing to work.
With this question, the author provides context to his question as well as evidence of work such as his code:
_git_clone ()
{
    case "$cur" in
    --*)
        __gitcomp_builtin clone
        return
        ;;
    esac
}
----------------------------------------------------------------------------------
# https://github.com/scop/bash-completion/blob/d2f14a7/bash_completion#L498
__ltrim_colon_completions() {
    if [[ "$1" == *:* && "$COMP_WORDBREAKS" == *:* ]]; then
        # Remove colon-word prefix from COMPREPLY items
        local colon_word=${1%"${1##*:}"}
        local i=${#COMPREPLY[*]}
        while [[ $((--i)) -ge 0 ]]; do
            COMPREPLY[$i]=${COMPREPLY[$i]#"$colon_word"}
        done
    fi
}


_git_clone() {
    case "$cur" in
    --*)
        __gitcomp_builtin clone
        return
        ;;
    *)
        argc=0
        for word in "${words[@]}"; do
            case "$word" in
            git|clone|--*)
                continue
                ;;
            *)
                argc=$((argc + 1))
                ;;
            esac
        done

        if [ $argc -le 1 ]; then
            __gitcomp "https://github.com/git/git https://github.com/python/cpython"
            __ltrim_colon_completions "$cur"
        fi
        ;;
    esac
----------------------------------------------------------------------------------
The author also provides what he worked on and unacceptable solutions. This has allowed many in the response section providing great answers.
Moreover, the author continues dialogue with those that were helping him.
}
```
I saw this question generate a lot of interest and work into this problem. I feel that this was a great question and the amount of technical knowledge shared between the author and those answering his question to be amicable and productive.

## Maybe this could've been researched...

```
https://stackoverflow.com/questions/54360790/intellij-take-standard-input-from-a-file

I didn't find this question to be poor. It was a standard question, however I found this question to be something more simple that maybe if the author did more research that he may have been able to find his answer himself.

The author needs to take a standard input from a file in IntelliJ Idea with the code:
$ java BinarySearch tinyW.txt < tinyT.txt
He asks how this is achievable with IntelliJ.

Although he recieved an answer, there was not as much views or answers. The answer seemed very sparse and quick as if it was a regurgitation of instructions rather than a discussion.
```

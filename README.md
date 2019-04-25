## 一、软件测试基础知识
### 1.分别介绍一下单元测试、集成测试、系统测试、验收测试、回归测试。
    （1）单元测试：最小模块的测试，可以是一个函数或子程序，一般由开发者在系统开发过程中进行执行。
    单元测试针对每一个程序模块进行正确性检验，检查各个程序 模块是否正确地实现了规定的功能。
    单元测试是测试的第一步，其依据是详细设计，单元测试应对模块内所有重要的控制路径设计测试用例，
    以便发现模块内部的错误。
    （2）集成测试：被测试系统的所有组件都集成在一起，找出被测试系统组件之间关系和接口中的错误。
    该测试一般在单元测试之后进行。
    ——自顶向下增式测试
    ——自底向上增式测试（常用）：
    (3)系统测试：是将通过确认测试的软件，作为整个基于计算机系统的一个元素，与计算机硬件、外设、
    某些支持软件、数据和人员等其他系统元素结合在一起，在实际运行环境下，对计算机系统进行全面的功能覆盖。
    （确认测试：由集成测试进入系统测试之前，需要对软件是否可以进入系统测试进行评价，这个过程称为确认测试）
    （4）验收测试：
    ——Alpha testing (α测试),是由一个用户在开发环境下进行的测试，也可以是公司内部的用户在模拟实际操作环境
    下进行的受控测试，Alpha测试不能由程序员或测试员完成。（受控的场所）
    ——Beta testing(β测试),测试是软件的多个用户在一个或多个用户的实际使用环境下进行的测试。开发者通常不在
    测试现场，Beta测试不能由程序员或测试员完成。（不受控的场所）
    （5）回归测试：在发生修改之后重新测试先前的测试用例以保证修改的正确性。理论上，软件产生新版本，都要进行
    回归测试。
### 2.请说一说黑盒与白盒的测试方法。
    （1）黑盒测试也称功能测试或数据驱动测试，它是在已知产品所具有的功能，通过测试来检测每个功能是否都能正常
    使用。在测试时，把程序看作一个不能打开的黑盒子，在不考虑程序内部结构和内部特性的情况下，测试者在程序接口
    进行测试。
       黑盒法着眼于程序外部结构，不考虑程序内部逻辑，针对软件界面和软件功能进行测试。常用的黑盒测试方法有：
     等价类划分法；边界值分析法；因果图法；场景法；正交实验设计法；判定表驱动分析法；错误推测法；功能图分析法
     （2）白盒测试也称结构测试或逻辑驱动测试，是针对被测单元内部如何进行工作的测试。它根据程序的控制结构设计
     测试用例，主要用于软件或程序验证。
       常用的白盒测试法：
       静态测试：不用运行程序的测试。
       动态测试：需要执行代码，通过运行程序找到问题。
       白盒测试中的逻辑覆盖覆盖包括语句覆盖、判定覆盖、条件覆盖、判定/条件覆盖、条件组合覆盖和路径覆盖。六种
       覆盖标准发现错误的能力呈由弱到强的变化。
### 3.软件测试的一般流程是怎么样的？
    （1）项目立项后，参加需求评审。
    （2）根据需求文档制定测试用例，然后进行用例评审。
    （3）项目提测后，执行用例，记录问题，及时有效地跟进问题的解决情况。
    （4）测试环境测试通过后，产品进行验收测试。
### 4.设计测试用例的方法有哪些？
    最常用的3种 等价类划分、边界值、场景法 
    （1）等价类划分 分为有效等价类和无效等价类，将测试的范围划分成几个互不相交的子集，从每个子集选出若干个有代表性的值作为测试用例。 
    （2）边界值：因为大多数错误都在输入输出的边界上，选取正好等于、刚刚大于、刚刚小于边界的值，如果边界附件取值不会导致程序出错，那么
    其他取值出错的可能性也就很小。 
    （3）场景法：划分不同的场景，然后逐一进行验证。
### 5.软件测试工程师在一个团队中，都需要做什么，有什么价值？
    （1）在产品需求会上，可以站在用户的角度，提一些贴合用户需求的建议。
    （2）测试阶段，根据自己对项目的了解和专业的测试技能 尽可能在项目上线前测出更多问题，保证产品质量 
    （3）对测试过程中出现的问题 合理有效的进行风险评估。
    （4）对质量严格把关 测试不通过的一定不能发布生产。

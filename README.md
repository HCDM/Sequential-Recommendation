# Sequential-Recommendation
This is a repository containing algorithms for sequential recommendation, like CAT and CoCoRec.

Paper 1: Déjà vu: A Contextualized Temporal Attention Mechanism for Sequential Recommendation (CAT) 

Abstract: Predicting users’ preferences based on their sequential behaviors in history is challenging and crucial for modern recommender systems. Most existing sequential recommendation algorithms focus on transitional structure among the sequential actions, but largely ignore the temporal and context information, when modeling the influence of a historical event to current prediction. In this paper, we argue that the influence from the past events on a user’s current action should vary over the course of time and under different context. Thus, we propose a Contextualized Temporal Attention Mechanism that learns to weigh historical actions’ influence on not only what action it is, but also when and how the action took place. More specifically, to dynamically calibrate the relative input dependence from the self-attention mechanism, we deploy multiple parameterized kernel functions to learn various temporal dynamics, and then use the context information to determine which of these reweighing kernels to follow for each input.

Link of the repository: https://github.com/Charleo85/seqrec/tree/master/cta

Paper 2: Category-aware Collaborative Sequential Recommendation (CoCoRec)

Sequential recommendation is the task of predicting the next items for users based on their interaction history. Modeling the dependence of the next action on the past actions accurately is crucial to this problem. Moreover, sequential recommendation often faces serious sparsity of item-to-item transitions in a user’s action sequence, which limits the practical utility of such solutions. To tackle these challenges, we propose a Category-aware Collaborative Sequential Recommender. Our preliminary statistical tests demonstrate that the in-category item-to-item transitions are often much stronger indicators of the next items than the general itemto-item transitions observed in the original sequence. Our method makes use of item category in two ways. First, the recommender utilizes item category to organize a user’s own actions to enhance dependency modeling based on her own past actions. It utilizes self-attention to capture in-category transition patterns, and determines which of the in-category transition patterns to consider based on the categories of recent actions. Second, the recommender utilizes the item category to retrieve users with similar in-category preferences to enhance collaborative learning across users, and thus conquer sparsity. It utilizes attention to incorporate in-category transition patterns from the retrieved users for the target user.

Link of the repository: https://github.com/RenqinCai/CoCoRec


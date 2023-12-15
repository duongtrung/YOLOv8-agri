# YOLOv8-agri

This is the supplimentary Github repository for our submitted paper to EAI Endorsed Transactions on Industrial Networks and Intelligent Systems. The pre-trained models will be available upon the acceptance.

\begin{table}[]
	\centering
	\caption{The performance of our YOLOv8-agri models on chicken and fish datasets. The best scores are in bold.}
	\label{tab:yolov8-argi}
	\resizebox{1.0\columnwidth}{!}{%
		\begin{tabular}{|l|ccc|ccc|}
			\hline
			\multicolumn{1}{|c|}{\multirow{2}{*}{Model}} & \multicolumn{3}{c|}{chicken data}                                                                                                                            & \multicolumn{3}{c|}{fish data}                                                                                                                               \\ \cline{2-7} 
			\multicolumn{1}{|c|}{}                       & \multicolumn{1}{l|}{mAP50}          & \multicolumn{1}{l|}{mAP50-95}       & \multicolumn{1}{l|}{\begin{tabular}[c]{@{}l@{}}training\\ time (h)\end{tabular}} & \multicolumn{1}{l|}{mAP50}          & \multicolumn{1}{l|}{mAP50-95}       & \multicolumn{1}{l|}{\begin{tabular}[c]{@{}l@{}}training\\ time (h)\end{tabular}} \\ \hline
			YOLOv8n-agri                                 & \multicolumn{1}{c|}{0.790}          & \multicolumn{1}{c|}{0.444}          & 0.734                                                                            & \multicolumn{1}{c|}{0.656}          & \multicolumn{1}{c|}{0.326}          & 0.729                                                                            \\ \hline
			YOLOv8s-agri                                 & \multicolumn{1}{c|}{0.852}          & \multicolumn{1}{c|}{0.463}          & 0.749                                                                            & \multicolumn{1}{c|}{0.668}          & \multicolumn{1}{c|}{0.322}          & 0.733                                                                            \\ \hline
			YOLOv8m-agri                                 & \multicolumn{1}{c|}{0.813}          & \multicolumn{1}{c|}{0.470}          & 0.799                                                                            & \multicolumn{1}{c|}{0.696}          & \multicolumn{1}{c|}{0.358}          & 0.816                                                                            \\ \hline
			YOLOv8l-agri                                 & \multicolumn{1}{c|}{\textbf{0.871}} & \multicolumn{1}{c|}{\textbf{0.491}} & 0.822                                                                            & \multicolumn{1}{c|}{\textbf{0.718}} & \multicolumn{1}{c|}{0.334}          & 0.826                                                                            \\ \hline
			YOLOv8x-agri                                 & \multicolumn{1}{c|}{0.792}          & \multicolumn{1}{c|}{0.441}          & 0.994                                                                            & \multicolumn{1}{c|}{0.717}          & \multicolumn{1}{c|}{\textbf{0.359}} & 0.895                                                                            \\ \hline
		\end{tabular}%
	}
\end{table}

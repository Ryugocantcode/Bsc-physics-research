
<h1>🧬 Research</h1>
<p><strong>Student:</strong> SUYOG BARAL | BSc Physics, Tri-chandra, Nepal<br>
<strong>Advisor:</strong> Prof. Arjun Acharya (Published in <i>J. Mol. Graph. Model.</i>, etc.)</p>

<table>
<tr><th>Stage</th><th>Status</th><th>Details</th></tr>
<tr><td>Research</td><td>Ongoing</td><td>Molecular docking + DFT of herbal compounds vs HDAC2 </td></tr>
<tr><td>Tools</td><td>Active</td><td>AutoDock Vina | Gaussian | MATLAB | MM/GBSA</td></tr>
<tr><td>Paper</td><td>Drafting</td><td>Target: <i>J. Publishing</i> | Expected Publishing 2026</td></tr>
</table>

<h2>Sample MATLAB Analysis (Binding Affinity)</h2>
<pre><code>% binding_plot.m
scores = [-8.2, -7.5, -9.1, -8.8];  % kcal/mol (your docking results)
compounds = {'Curcumin', 'Resveratrol', 'Quercetin', 'Control'};
bar(scores);
set(gca, 'XTickLabel', compounds, 'XTickLabelRotation', 45);
ylabel('Binding Affinity (kcal/mol)');
title('Top Herbal HDAC2 Inhibitors');
saveas(gcf, 'docking.png');
</code></pre>
<img src="docking.png" alt="Docking Results">

<p><a href="paper_draft.pdf">📄 Preprint Draft (PDF)</a> | 
<a href="data.csv">📊 Raw Docking Scores</a></p>

<hr>
</body>
</html>

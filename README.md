# Insurance-

```python 

plt.figure(figsize=(10, 5))
sns.barplot(x='age_segment', y='charges', hue='age_segment',
            data=insurance, estimator='mean', palette='coolwarm', legend=False)
plt.title('Average Charges by Age Segment')
plt.ylabel('Average Charges')
plt.show()

```

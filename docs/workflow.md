# Git workflow

1. Start a focused branch: feat/, fix/, docs/ or chore/.
2. Make small, descriptive commits; inspect diffs before committing.
3. Open a pull request describing behavior, validation and limitations.
4. Check mobile layout, EN/Arabic parity, RTL, links and any changed forms.
5. Review and merge; deploy the exact reviewed commit through a separately configured hosting workflow.

Bootstrap commit initializes the default branch. Subsequent work uses pull requests. Do not force-push the default branch.

## Assets
Keep editable design sources under design/. Keep optimized, approved website assets under public/images/. Track each image's origin and approval in design/assets.csv. Large photo/video originals should be stored externally; Git tracks their references. Never commit secrets or applicant/customer records.

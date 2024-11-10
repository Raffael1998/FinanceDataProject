# FinanceDataProject
First finance data project to play around

If error ModuleNotFoundError: No module named 'distutils' after importing pandas-datareader

The fix is to change
'from distutils.version import LooseVersion'
to
'from packaging.version import Version as LooseVersion'
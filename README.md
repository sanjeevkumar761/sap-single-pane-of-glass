# Single pane of glass for SAP on Azure
Provides example Azure workbooks to setup a single pane of glass for monitoring SAP landscapes.

It makes use of tags and currently uses following tags, which need to be SAP app servers and HANA VMs.  
tier=development
workloadtype=appserver or hanadb
appsid=<SAP SID>

First example is a workbook https://raw.githubusercontent.com/sanjeevkumar761/sap-single-pane-of-glass/master/sap-landscape-view.json which allows to select SAP SID and monitors key performance metrics for SAP App Servers and HANA DB.


# Disclaimer
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

This source code is just an example and it does not represent any software or product or service from my employer Microsoft. It is not an official Microsoft artifact and it is not endorsed in any way by Microsoft. You should exercise your own judgement and prudence before using it. There is no one who is actively maintaining or supporting this project.

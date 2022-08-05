# k8s-vpa-helm-chart

This is an unofficial Helm chart for the Kubernetes Vertical Pod Autoscaler (VPA). If you want to learn about the autoscaler first, see https://github.com/kubernetes/autoscaler/tree/master/vertical-pod-autoscaler for details.


## DISCLAIMER

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

For the full license, see:
https://github.com/michiwerner/k8s-vpa-helm-chart/blob/main/LICENSE

## Installation

Using Helm 3.x, the installation is a two-step process.

First, add the repository:

<pre><code>helm repo add k8s-vpa https://michiwerner.github.io/k8s-vpa-helm-chart/helm-charts</code></pre>

Then, install the chart:

<pre><code>helm install -n kube-system vpa k8s-vpa/vpa</code></pre>


## Usage

Please refer to the official documentation to learn how to configure and use the VPA: https://github.com/kubernetes/autoscaler/tree/master/vertical-pod-autoscaler#contents
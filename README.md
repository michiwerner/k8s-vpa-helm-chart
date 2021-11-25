# k8s-vpa-helm-chart

This is an unofficial Helm chart for the Kubernetes Vertical Pod Autoscaler (VPA). If you want to learn about the autoscaler first, see https://github.com/kubernetes/autoscaler/tree/master/vertical-pod-autoscaler for details.


## DISCLAIMER

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

https://github.com/michiwerner/k8s-vpa-helm-chart/blob/main/LICENSE


## Usage

Using Helm 3.x, the installation is a two-step process.

First, add the repository:

<pre><code>helm repo add k8s-vpa https://michiwerner.github.io/k8s-vpa-helm-chart/releases</code></pre>

Then, install the chart:

<pre><code>helm install -n kube-system k8s-vpa/vpa</code></pre>
